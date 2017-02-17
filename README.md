What is "Island"
----------------

"Island" is a sandbox environment to clone selected apps and isolate them from accessing your personal data outside the sandbox (including call logs, contacts, photos and etc) even if related permissions are granted. Device-bound data (SMS, IMEI and etc) is still accessible.

Isolated app can be frozen on demand, with launcher icon vanish and its background behaviors completely blocked.

How does it work
----------------

Island takes advantage of the "managed profile" feature on Android 5.0+, which is the also the base of "Android for Work", to create an isolated sandbox for apps and their data.

App needs to be cloned in Island first. Afterwards, the clone can run parallel aside from the original one. (even with different accounts signed-in) It can be frozen on demand by Island. (NO ROOT REQUIRED)

Currently, all operations are manual in Island. There's a plan to integrate Greenify with Island to provide automatic freezing feature.

Common use cases
----------------

- **Freeze frequently woken apps.** Clone it into Island and uninstall the original one outside. Then you can freeze it to fully block its background behaviors. Remember to create launch shortcut for quick de-freezing and launching.
- **Prevent permission-hungry apps from accessing your private data.** Sometimes runtime-permission may not be the solution, especially if the app refuses to work without certain permissions. App clones running in Island cannot access your contacts, call logs and sniff other apps outside. **But SMS and location are exceptions since they are bound to device.**
- **Use two accounts of the same app parallel.** Clone it into Island and login the other account inside.
- **Archive rarely used apps.** Like the first case, keep them frozen until the next time you need it.
- **Hide your private apps.**

Discussion and feedback
-----------------------

[XDA thread](https://forum.xda-developers.com/android/apps-games/closed-beta-test-incoming-companion-app-t3366295)

DISCLAIMER
----------

This beta version may be dangerous on some Android devices, it may cause boot-loop and even brick your device. The purpose of closed beta exclusive for advanced users is to widely test and improve the device compatibility. Don't install it on your daily device and remember to BACKUP FIRST.