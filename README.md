Device Checklist for Asus Zenfone Max Pro M2 (X01BD)
===================================================

Working
-------
* Actors: Torchlight
* Cellular: Carrier info, signal strength
* Cellular: Change audio routings (Speakerphone, Earphone)
* Cellular: Data connection
* Cellular: Incoming, outgoing calls
* Cellular: SMS in, out
* Cellular: Switch preferred SIM for calling and SMS - only for devices that support it
* Cellular: Voice in calls
* GPU: Boot into SPinner animation and Lomiri UI
* Misc: Battery percentage
* Misc: Date and time are correct after reboot (go to flight mode before)
* Misc: Offline charging (Power down, connect USB cable, device should not boot to UT)
* Misc: Online charging (Green charging symbol, percentage increase in stats etc)
* Misc: SD card detection and access - only for devices that support it
* Misc: Shutdown / Reboot
* Sensors: Rotation works in Lomiri
* Sensors: Touchscreen registers input across whole surface
* Sound: Earphones detected, volume control ok
* Sound: Loudspeaker, volume control ok
* Sound: Microphone, recording works
* Sound: System sounds and effects plays correctly (Camera shutter, Screenshot taken, Notifications)
* USB: ADB access
* USB: External monitor - only for devices that support it
* USB: MTP access
* WiFi: Driver loaded at startup
* WiFi: Enable/disable and flightmode works
* WiFi: Hotspot can be configured, switched on and off, can serve data to clients
* WiFi: Persistent MAC address between reboots

Working with additional steps
-----------------------------
* Cellular: Enable/disable mobile data and flightmode works (need to manually enable-disable data after flight mode)

Not working
-----------
* Actors: Manual brightness
* Actors: Notification LED
* Actors: Vibration (works in QML apps, notifications, keyboard)
* Bluetooth: Driver loaded at startup
* Bluetooth: Enable/disable and flightmode works
* Bluetooth: Pairing with headset works, volume control ok
* Bluetooth: Persistent MAC address between reboots
* Camera: Ensure proper cameras are in use (On device with more than 2 logical cameras)
* Camera: Flashlight
* Camera: Photo
* Camera: Switch between back and front camera
* Camera: Video
* Sensors: Automatic brightness
* Sensors: Proximity works during a phone call
* Sensors: Fingerprint reader, register and use fingerprints (Halium >=9.0 only)
* Misc: Reset to factory defaults (TWRP is used)

To be tested
------------
* Cellular: MMS in, out
* Cellular: PIN unlock
* Cellular: Switch connection speed between 2G/3G/4G works for all SIMs
* Endurance: Battery lifetime > 24h from 100%
* Endurance: No reboot needed for 1 week
* GPU: Hardware video decoding
* Misc: Anbox patches applied to kernel
* Misc: AppArmor patches applied to kernel
* Misc: logcat, dmesg & syslog do not spam errors and service restarts
* Misc: Recovery image builds and works
* Sensors: GPS
