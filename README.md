M2_logs
=======

M2 CyanogenMod bringup logs


Bug list
----------


Working:
--------
Display

Audio playback

Internal SDcard

Screenshot

Not working:
-----------
Camera (http://pastebin.com/Te5CTy9a)

WiFi (D/WifiHW  (  847): Unable to unload driver module "wlan": No such file or directory)

Bluetooth


Untested:
--------
RIL (probably not working)

Audio recording

External SDcard

Video playback

NFC

GPS

Other issues (Pre-alpha build):
--------------------------------
- Touchscreen doesn't work on every boot
- Stock browser disabled purposely to build faster
- System UI may FC (related to RIL issues)
- Overlay (display HAL, msm_fb) logspam: http://pastebin.com/RWp0UF8B

Pre-alpha build: Coming soon!
ONLY FOR LOG COLLECTING AND BUG FIXING!



Please use adb "logcat *:E" instead of "adb logcat". - Lozohcum
