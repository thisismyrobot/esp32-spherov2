# ESP32 Sphero V2 controller

Connecting to and controlling a Sphero V2 (SPP Bluetooth Classic) from an
ESP32 running Arduino requires a special combination of ESP32 board software
(1.0.2) and the replacement of the BluetoothSerial code.

This repo is a working Arduino project example of connecting to and moving a
Sphero 2.0. You need to put the contents in a folder named `esp32-spherov2`
to open as an Arduino project. It was extracted from another project so you
can probably whittle it down further.

It doesn't yet read async packets back from the Sphero, but I'll add that if
I get it working.

Otherwise, there won't be further development here, this is just to get the
code out there after many hours of debugging.

This wouldn't have been possible without this comment, thank you:
https://github.com/espressif/arduino-esp32/issues/3916#issuecomment-625486992
