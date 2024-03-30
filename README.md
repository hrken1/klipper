Welcome to the Amken fork of the Klipper project!

This fork supports the Amken Bunny Board and the Amken Baby Bunny Extruder board hardware.
The following features are implemented in this fork

1. Support for UART1 on the RP2040
2. Support for selecting different UART pins on the RP2040 in Makeconfig
3. Added suport for direct loading of checksum .s file for the following Winbond memory chips (Amken Bunny and Baby Bunny boards use the W25Q128JV chip, which is unsupported in the mainline of Klipper)
    WINBOND W25Q080 1MB, WINBOND W25Q16JV 2MB, WINBOND W25Q64JV 8MB, WINBOND W25Q128JV 16MB, GENERIC_03H with CLKDIV 4

[![Klipper](docs/img/klipper-logo-small.png)](https://www.klipper3d.org/)

https://www.klipper3d.org/

Klipper is a 3d-Printer firmware. It combines the power of a general
purpose computer with one or more micro-controllers. See the
[features document](https://www.klipper3d.org/Features.html) for more
information on why you should use Klipper.

To begin using Klipper start by
[installing](https://www.klipper3d.org/Installation.html) it.

Klipper is Free Software. See the [license](COPYING) or read the
[documentation](https://www.klipper3d.org/Overview.html). We depend on
the generous support from our
[sponsors](https://www.klipper3d.org/Sponsors.html).
