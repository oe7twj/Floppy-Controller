# Floppy-Controller
Controller board for a Commodore 1541 floppy drive

This is Hardware Extension for a 1541 Floppy Drive.
(The 1541 is a retro hardware from Commodore)


### Nessecary Hardware:
* an old 1541 or 1541-II Floppy Drive
* optionally a Trackduino hardware (for track display)
  https://github.com/oe7twj/TrackDuino
* an Arduino Nano [3€]
* an OLED 128x64 display [3€]
* optionally a I2C LCD display instead of OLED
* a Rotary Encoder [1€]


## Nessecary Software:
- Arduino Workbench
- Arduino Lib: LCD Menu Lib 2: https://github.com/Jomelo/LCDMenuLib2
- Arduino Lib: U8g2lib: https://github.com/olikraus/u8g2


## Features:
* Write protection switch (read only, write always, auto)
* ROM selector (switch between up to 4 DOS Kernal)
* Select device number from 8 to 11
* settings are saved in Eprom of the Arduino
* Info Display



