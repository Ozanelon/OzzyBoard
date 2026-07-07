# OzzyBoard

![OzzyBoard 3D Render](https://github.com/Ozanelon/OzzyBoard/blob/main/photos/OzzyBoard.png?raw=true)

A custom RP2040-based development board, built as a learning project.

## About

This project follows [KaiPereira's devboard tutorial](https://github.com/KaiPereira/build-a-devboard) 
as a base, with the following custom additions:

- One addressable RGB LED (WS2812B) for status indication
- I2C0 breakout header (with pull-up resistors) for external sensors
- SPI1 breakout header for external peripherals (SD card, displays, etc.)

## Production
You can find the ready-to-print Gerber files, Bill of Materials (BOM), and Component Placement List (CPL) in the `production/` directory.

## Status

🚧 In progress — Manufacturing phase

## Hardware

- **MCU:** Raspberry Pi RP2040
- **Flash:** W25Q128JVS (16MB QSPI flash)
- **Power:** USB-C input, MCP1700x-3302E/TT 3.3V LDO
- **Tools:** KiCad

## Author

Built by [Ozan Koçer](https://github.com/Ozanelon) as part of Hack Club.
