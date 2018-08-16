# sam-fusee-launcher
Fusee Launcher for the SparkFun SAMD21 breakout boards (or in this fork, mostly for Genuino Zero).

Based on [Fusee Launcher](https://github.com/reswitched/fusee-launcher).

Built and tested with Arduino "IDE".

[Video of it in action](https://youtu.be/VCyeExfVRiE)

## Tips and notes

- Don't forget to install USBHost library.
- You can convert payloads with [this script](https://github.com/atlas44/sam-fusee-launcher/issues/2).
- If you find yourself unable to be able to flash the SAMD21 after the first flash, short RST and GND while it's plugged to a pc and try again.

## Differences from atlas44's version

- Converted for use with Arduino "IDE" and not platformio (because that thing's just a big pain to set up)
- Actually does compile
- Includes useful links

## Supported boards:
- [Arduino/Genuino Zero](https://store.arduino.cc/usa/arduino-zero) (also the various clones)
- [SparkFun SAMD21 Dev Breakout](https://www.sparkfun.com/products/13672)
- [SparkFun SAMD21 Mini Breakout](https://www.sparkfun.com/products/13664)

Note that the Switch does NOT provide power in RCM, so you will need to power the boards from a battery or something else!
