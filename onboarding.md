# Onboarding

After thorough investigation [@agg23](https://github.com/agg23) determined that it is unlikely to be able to get a factory reset device into a "near-provisioned" state due to the thoroughness of the code.

## Investigations

* Actual provisioning process requires a multi-step back and forth with network calls.
  * All network calls are hardcoded to use a embedded cert in the APK.
  * The cert can be bypassed if you can set `persist.humane.ironman.config.services.onboardingGatewayUri` to a URL containing a port other than 443 (or none). This property is not writable from `shell`.
  * Strangly `persist.humane.service.env.type` is writable from `shell`, but pointing it to another endpoint doesn't actually get you anywhere.
* There is `humaneinternal.system.ProvisioningService`, which is bindable. You can call `bindUser`, which is the final step in provisioning, but it still makes another network request, so this doesn't get you anywhere.
* You can not directly write fake credentials into the `AndroidKeyStore`.
* There are two test activities marked under `experiments` for provisioning. Both of those just test method calls but don't persist anything to disk in the correct locations.

## Cleaning

* The act of disabling onboarding (`pm disable-user --user 0 humane.experience.onboarding`) causes the correct process to start such that you get the normal launcher. However, certain things aren't configured, so `hu.ma.ne.ironman` constantly tries to start `hu.ma.ne.ironman/humaneinternal.system.CentralService`, which fails, which it then repeats in ~300ms, over and over again. This state is persistent once you have disabled onboarding once. Disabling `ironman` itself (`pm disable-user --user 0 hu.ma.ne.ironman`) stops the errors.