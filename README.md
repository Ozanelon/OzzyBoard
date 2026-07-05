# OzzyBoard

A custom RP2040-based development board, built as a learning project.

## About

This project follows [KaiPereira's devboard tutorial](https://github.com/KaiPereira/build-a-devboard) 
as a base, with the following custom additions:

- One addressable RGB LED (WS2812B) for status indication
- I2C0 breakout header (with pull-up resistors) for external sensors
- SPI1 breakout header for external peripherals (SD card, displays, etc.)

## Status

🚧 In progress — schematic design phase

## Hardware

- **MCU:** Raspberry Pi RP2040
- **Flash:** W25Q128JVS (16MB QSPI flash)
- **Power:** USB-C input, NCP1117-3.3 LDO
- **Tools:** KiCad

## Author

Built by [Ozan Koçer](https://github.com/Ozanelon) as part of Hack Club.
