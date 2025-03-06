# Kastenwagen 1840 Chunky ISO RP2040

![Kastenwagen 1840](https://diplomacyvariants.files.wordpress.com/2022/01/late-harvest-on-kastenwagen.png)

Kastenwagen 1840 is a 40% keyboard with a mini-numpad and dedicated arrows.  The main alpha block is 13.75u long, allowing for more dedicated punctuation keys (or non-English letters) to be paired with common Minivan-like mod keys.

Kastenwagen 48 is a similar keyboard that replaces the mini-numpad with a small macro column.

For more information, join the [NoPunIn10Key Discord](https://discord.gg/sku2Y6w).

## RP2040 PCB Port
The PCB in this branch was ported for the use of a RP2040 Community Edition MCU, no Elite-C support! As the pinout of the Elite-C and the RP2040 community footprint is not exactly the same, one of the status LEDs was not working when using such an MCU. For that case, I switched the KiCad files to use a 0xCB Helios as base and changed some of the routing for the new pinout. All status LEDs are now confirmed working.

## Credit

* Keyboard Maintainer: [Alex Ronke](https://nopunin10did.com/), also known as [NoPunIn10Did](https://github.com/NoPunIn10Did)
* Hardware Supported: Kastenwagen 1840 (2021 June)
* Hardware Availability: Currently by request only
