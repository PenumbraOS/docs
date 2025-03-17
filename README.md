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