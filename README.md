# M4-Shim
M4 Shim for PoE-FeatherWing, functionally equivalent to Feather M4 Express

### Description

This is an adaptation of the excellent
[Adafruit Feather M4 Express](https://github.com/adafruit/Adafruit-Feather-M4-Express-PCB),
redesigned specifically for use with the equally excellent
[PoE-FeatherWing](https://hackaday.io/project/168356-poe-featherwing).

The goal was to create a compact system with Power over Ethernet, Ethernet connectivity and
a powerful processor capable of supporting [CircuitPython](https://circuitpython.org/).
Because of the bulky RJ45 jack and flyback transformer on the PoE-FeatherWing, it was not
possible to mount a traditional Feather on top.  This redesign takes the relevant circuitry
of the Adafruit Feather M4 Express and shapes it so it fits in the gaps between the
tall components of the PoE-FeatherWing.  This way it can be mounted on top for an extremely
compact solution.

The only thing missing versus the Feather M4 Express is the battery support circuitry,
which did not seem necessary in a PoE design.

### License

This redesign by Silicognition LLC is licensed as Creative Commons Attribution/Share-Alike,
just like the Adafruit Feather M4 Express it is based on.

Original Adafruit license statement:

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See LICENSE for additional details.

