# xBridge_Simblee
RFDuino Limitter LBridge code converted to work with Simblee
Thanks to @keencave @FPV-UAV @JoernL for work on the Arduino and RFDuino code.

This code is still in alpha stage

pin mapping:

Simblee   BM019
GPIO 2    DIN
GPIO 3    MISO
GPIO 4    SCK
GPIO 5    MOSI
GPIO 6    SS
+3V       VDD/SSO
GND       GND

Simblee programming pins
GND
RESET
GPIO 0 / AREF
GPIO 1
+3V is optional, works w/o if Simblee is powered with LiPo, this way you can youe just 4 wires.
