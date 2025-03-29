# kicad-displays

This repository contains the KiCAD footprints and symbols for the following displays.

Please note that none of the symbols have linked footprints, as some displays can be soldered, while others need a FPC connector.

## Display Symbols

The pinout for the various displays seems to be somewhat standardized, but there is no guarantee that the pinout will be the same across all manufacturers.
However, most Aliexpress displays seems to follow the same pinout. The pinouts for each display can be found in either the [pinout folder](pinouts/) or by clicking the links below directly to their respective pinout.

ST7789
- [8 pin 1-bit SPI interface](pinouts/st7789_8p_1spi.md)
- [12 pin 1-bit SPI interface](pinouts/st7789_12p_1spi.md)
- [18 pin 1-bit SPI interface, with touch](pinouts/st7789_18p_1spi_touch.md)
- [30 pin 16-bit RGB interface](pinouts/st7789_30p_16rgb.md)
- [30 pin 16-bit RGB interface, with touch](pinouts/st7789_30p_16rgb_touch.md)

GC9A7
- [12 pin 1-bit SPI interface](pinouts/gc9a01_12p_1spi.md)

ST7701
- [40 pin 18-bit RGB interface](pinouts/st7701_40p_18rgb.md)
- [40 pin 18-bit RGB interface, with touch](pinouts/st7701_40p_18rgb_touch.md)


## FPC Footprints

The FPC can be either soldered directly onto the PCB if the end are double sided, or it needs to be connected via a FPC connector if one side is covered with a plastic piece.