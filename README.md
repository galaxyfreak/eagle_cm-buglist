Kernel 3.10 bringup status
=======

eagle (CM12)
----------



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

- MTP

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

- FM Radio

- USB Host & OTG

- Camera
(Not implemented yet)


Untested:
-----------

- Video playback
(will check later, rebuilding atm)

- GPS
(I'm indoors, can't test now)
