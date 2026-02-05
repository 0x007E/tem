[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/tem) ![Build](https://github.com/0x007e/tem/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `TEM` - TWI EEPROM Module

The `TEM` is a board with an [AT24CM0X](#additional-information) `EEPROM` or any other `EEPROM` that fits the pin setting of the board. The board itself is driven with a voltage from `3V3`-`5V`. The `EEPROM` can be protected from being written with the onboard switch `SW1`.

> The address setup of the `EEPROMs` can be setup with Jumper `JP1`/`JP2`for the first `EEPROM` and Jumper `JP3`/`JP4` for the second `EEPROM`.

| Experience | Level |
|:------------|:-----:|
| Soldering   | ![?%](https://progress-bar.xyz/20?progress_color=00ff00&suffix=%20Medium&width=120) |
| Mechanical    | ![?%](https://progress-bar.xyz/30?progress_color=ff0000&suffix=%20Low&width=120) |

# Downloads

| Type      | File               | Description              |
|:---------:|:------------------:|:-------------------------|
| Schematic | [pdf](https://github.com/0x007E/tem/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/29791/main/files) | Schematic files |
| Board | [pdf](https://github.com/0x007E/tem/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/29791/main/files) | Board file |
| Drill | [pdf](https://github.com/0x007E/tem/releases/latest/download/drill.pdf) | Drill file |
| PCB | [zip](https://github.com/0x007E/tem/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/tem/releases/latest/download/kicad.tar.gz) |  	KiCAD/Gerber/BoM/Drill files |
| Mechanical | [zip](https://github.com/0x007E/diu/releases/latest/download/freecad.zip) / [tar](https://github.com/0x007E/diu/releases/latest/download/freecad.tar.gz) | FreeCAD/Housing and PCB (STEP) files     |

# Hardware

The pcb is created with `KiCAD`, the housing with `FreeCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system. After placing and soldering the top parts, the board has to be cut off in the middle (white edge).

### Top Layer

![Top Layer](https://github.com/0x007E/tem/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/tem/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link               | Description              |
|:----------:|:------------------:|:-------------------------|
| AT24CM02 | [pdf](https://ww1.microchip.com/downloads/en/DeviceDoc/AT24CM02-I2C-Compatible-Two-Wire-Serial-EEPROM-2-Mbit-262,144x8-20006197C.pdf) | 2-MBit serial EEPROM dataseheet |
| AT24CM01 | [pdf](https://ww1.microchip.com/downloads/en/DeviceDoc/AT24CM01-I2C-Compatible-Two-Wire-Serial-EEPROM-Data-Sheet-20006170A.pdf) | 1-MBit serial EEPROM datasheet |

---

R. GAECHTER
