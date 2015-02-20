M2 CyanogenMod 12 on Kernel 3.10 bringup status
=======


Bug list
----------


Working:
--------

- GSM

- Mobile Data

- Display

- Audio playback

- External SDcard

- Internal SDcard

- Notification LED

- Deepsleep

- NFC


Not working:
-----------

- Audio recording

- WiFi
(probably needs config adjustments)

- Bluetooth
(unstable, turns on on boot, not working after that, can cause reboots)

- Recovery
(working, but have sony bootlogo over it. Genius.)

- Sensors
(We've just got a new HAL, one expected it's working, but nope)

- USB Host & OTG

- Camera
(Not implemented yet)


Untested:
-----------

- Video playback
(will check later, rebuilding atm)

- MTP
(worked 2 days back, gotta recheck)

- GPS
(I'm indoors, can't test now)

- FM Radio
(Lazy to untangle my headphones atm)
