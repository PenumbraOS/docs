# Documentation

This repo contains various findings by the openPin team. This data is presented to foster a community of learning and experimentation.

## Access Mechanisms

The only infiltration method we have at the moment is through ADB with the leaked Humane ADB certificate. Most likely this is all we will ever have.

## Difficulties

The Pin OS is extremely locked down, mostly through custom SELinux configuration. Many common operations such as networking is completely blocked off from use by user permission apps (such as what we would install normally).

The different communication methods we've found blocked are:

* Direct network access
* DNS
* Sockets
* Unix domain sockets (local sockets) - Almost works but does not allow app <-> shell communication
* Named pipes

You are able to communicate with another process via files. The `shell` user (ADB) has networking permission, so it can act as a bridge from user apps to the world (see [pushPin](https://github.com/openaipin/pushPin) for an implementation of this).

Other notable blocked APIs are:

* Touchpad access - No access to gestures or raw events
  * Data can again be intercepted by the `shell` user and sent to userland processes

## Binder

Binder is only allowed in a very shallow way due to the SELinux policy:

```
(neverallow untrusted_app_all service_manager_type (service_manager (add)))
(neverallow untrusted_app_all protected_service (service_manager (find)))
```

So you can't connect or register to most Binder services. However, there are some that are available:

```
(allow untrusted_app_all servicemanager (service_manager (list)))
(allow untrusted_app_all audioserver_service (service_manager (find)))
(allow untrusted_app_all cameraserver_service (service_manager (find)))
(allow untrusted_app_all drmserver_service (service_manager (find)))
(allow untrusted_app_all mediaserver_service (service_manager (find)))
(allow untrusted_app_all mediaextractor_service (service_manager (find)))
(allow untrusted_app_all mediametrics_service (service_manager (find)))
(allow untrusted_app_all mediadrmserver_service (service_manager (find)))
(allow untrusted_app_all nfc_service (service_manager (find)))
(allow untrusted_app_all radio_service (service_manager (find)))
(allow untrusted_app_all app_api_service (service_manager (find)))
(allow untrusted_app_all vr_manager_service (service_manager (find)))
```

Luckily, both `nfc` and `radio` are defined as "app contexts", and thus are accessible via [CVE-2024-31317](https://github.com/agg23/cve-2024-31317/). This is the communication method utilized by [the PenumbraOS SDK](https://github.com/penumbraOS/sdk).

This also prevents app to app communication (so no `untrusted_app` to `system_app`).

## Services

- Services cannot be started directly using `startService` from `untrusted_app`. It appears implicit starts using `bindService` work, but if you want the service to stay persistent using `startService`, it always throws an error that the app is in the background, even when it clearly is not.
