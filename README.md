# HP / Agilent / Keysight 34420A

Manuals and firmware images for the 34420A Nano Volt / Micro Ohm Meter, a
7½-digit two-channel nanovoltmeter and micro-ohmmeter of 1994 vintage.

## Manuals

**[34420A User's Manual](docs/34420A_Users_Manual.pdf)** — 264 pages covering
operation, programming, calibration and service, consolidated from all five
published editions. Each Keysight edition carries less than the
Hewlett-Packard edition before it. This one restores the specification
chapter, the chapter on applying those specifications, and the Quick Start
section on resistance measurement, all of which were dropped after the second
edition; folds in the SPRT manual update that was never merged into any
edition; and adds the performance verification, adjustment and service
procedures from the Service Guide as chapters 9 and 10. The figures are the
original artwork.

**[34420A Technical Service Manual](docs/34420A_Technical_Service_Manual.pdf)**
— 86 pages covering the instrument's processor and memory system, firmware
organisation, remote command set and calibration data.

**[34420A Schematics](docs/34420A_Schematics.pdf)** — 13 sheets: the
component locators for the 34420-66501 and 34420-66502 boards, the block
diagram, and the ten schematic sheets from input and protection through to
the display and keyboard.

## Firmware

`firmware/` holds the three main-processor ROM images, 256 KB each, for
programming a 27C020 or equivalent.

| File | Part number | Revision |
|---|---|---|
| `HP_34420a_88851_REV5.0_Fw.bin` | 34420-88851 | 5.0 |
| `Agilent_34420-88871_REV9.0_Fw_AM27C020.bin` | 34420-88871 | 9.0 |
| `KS_34420-88872_REV10.0_fw_AT27C020.bin` | 34420-88872 | 10.0 |

---

Compiled by Jared Cabot, <jetstreamtechnology@protonmail.com>, with Claude
(Anthropic).

Not a publication of Hewlett-Packard, Agilent Technologies or Keysight
Technologies, not endorsed by them, and not a substitute for the
manufacturer's own documentation. Trade names are used for identification
only.
