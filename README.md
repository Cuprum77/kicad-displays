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
Due to the large variety of possible footprints, only a few will be included in this repository.

Footprints are located in the [footprints folder](kicad-displays.pretty/).

Currently the following footprints are included:
- Soldered 12 pin, outline for 1.47" display
- Soldered 18 pin, outline for 1.69" display

If you want to create your own footprints for soldered FPC, you can use the guidelines found in [footprints_guide.md](footprints_guide.md).

### FPC Connector Footprints

For FPC connectors, use the manufacturer provided footprint or create one based on the provided manufacturer datasheet.
While the pitch of the FPC varies, most common ones are 0.5mm and 0.7mm.
There will not be any footprints for FPC connectors in this repository, as they are very specific to the manufacturer of the connector, and often have variations that make them incompatible with each other.

## 3D Models

There are also 3D models for the following screens:

ST7789
- [1.47" 12 pin display](3d/st7789_12p_1spi_1_47inch.step)

ST7701
- [3.99" 40 pin display](3d/st7701_40p_18rgb_3_99inch.step)

## Contributing

If you want to contribute to this repository, please read the [contributing guide](CONTRIBUTING.md) first.

## License

This project is licensed under CERN Open Hardware License Version 2 - Strong Reciprocity (CERN-OHL-S-2.0). See [LICENSE](LICENSE) for more details.