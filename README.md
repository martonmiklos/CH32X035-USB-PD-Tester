### What?

[This is the clone of this project](https://github.com/wagiminator/CH32X035-USB-PD-Tester)

Differences:
- Kicad 7+ (instead EasyEda)
- More generic pushbuttons
- Added programmer header
- Added load switch (for testing purposes)
- Changed voltage regulator to 3V3 as the
- Adoptable for LCDs with different pinouts (some exists with swapped GND and VDD pins)

![board view](https://raw.githubusercontent.com/martonmiklos/CH32X035-USB-PD-Tester/master/boardview.png "Board")

DO NOT BUILD IT YET. Mahor fuckups discovered during board bringup:
- The voltage regulator is not capable of supplying enought current to the LVD
