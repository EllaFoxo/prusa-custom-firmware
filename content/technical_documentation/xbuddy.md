---
weight: 302
title: "xBuddy"
draft: false
toc: true
description: "The mainboard found on the MK4 and Core One series"
date: "2025-12-07T00:10:31+01:00"
lastmod: "2025-12-07T00:10:31+01:00"
tags: ["xBuddy", "MK3.9", "MK3.9S", "MK4", "MK4S", "Core One", "Core One+", "Core One L"]
---

## List of printers using this board
---
- Prusa MK4
- Prusa MK4S
- Prusa Core One
- Prusa Core One L

<br/>

## Technical Specification
---

| Part                     | Value                         |
|:-------------------------|:------------------------------|
| MCU                      | STM32F427 (ZIT6)              |
| Flash                    | 2MiB                          |
| SRAM                     | 256KiB                        |
| Prusa Bootloader         | 128KiB (with 512 byte offset) |
| Application Start Offset | 0x8020200                     |

<br/>

## Electrical Schematics
---

- [FDM-xBUDDY-44.pdf](/files/schematics/FDM-xBUDDY-44.pdf)

<br/>

## Firmware Dumps
---

These firmware files are direct binary dumps from the flash memory of the xBuddy board. They serve as a safety net,
in case you accidentally do something stupid to brick your bootloader.  
To flash these, you will need to enter DFU mode.

#### Prusa MK4/S
- [Firmware v6.4.0 (25-Nov-2025)](/files/firmware_dumps/prusa_mk4s_6_4_0_2025_11_25.bin)

<br/>

## Option Bytes

Stock option configuration for the F427 MCU.

```json
{
  "deviceId" : 1049,
  "bitNameToValue" : {
    "RDP" : 170,
    "SPRMOD" : 0,
    "BOR_LEV" : 3,
    "BFB2" : 0,
    "WDG_SW" : 1,
    "nRST_STOP" : 1,
    "nRST_STDBY" : 1,
    "WRP0" : 1,
    "WRP1" : 1,
    "WRP2" : 1,
    "WRP3" : 1,
    "WRP4" : 1,
    "WRP5" : 1,
    "WRP6" : 1,
    "WRP7" : 1,
    "WRP8" : 1,
    "WRP9" : 1,
    "WRP10" : 1,
    "WRP11" : 1,
    "WRP12" : 1,
    "WRP13" : 1,
    "WRP14" : 1,
    "WRP15" : 1,
    "WRP16" : 1,
    "WRP17" : 1,
    "WRP18" : 1,
    "WRP19" : 1,
    "WRP20" : 1,
    "WRP21" : 1,
    "WRP22" : 1,
    "WRP23" : 1
  }
}
```

<br/>

## Sources
---

- [Prusa Open Source](https://www.prusa3d.com/page/open-source-at-prusa-research_236812/)

<br/>
