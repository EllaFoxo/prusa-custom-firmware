---
weight: 302
title: "Buddy"
draft: false
toc: true
description: "Prusa Mini and Mini+ mainboard"
date: "2025-12-07T00:10:31+01:00"
lastmod: "2025-12-07T00:10:31+01:00"
tags: ["xBuddy", "Mini", "Mini+"]
---

## List of printers using this board
---
- Prusa Mini
- Prusa Mini+

<br/>

## Technical Specification
---

| Part             | Value            |
|:-----------------|:-----------------|
| MCU              | STM32F407 (VGT6) |
| Flash            | TBC              |
| SRAM             | TBC              |
| Prusa Bootloader | TBC              |

<br/>

## Electrical Schematics
---

- [BUDDY_v1.0.0.pdf](/files/schematics/BUDDY_v1.0.0.pdf)

<br/>

## Firmware Dumps
---

These firmware files are direct binary dumps from the flash memory of the Buddy board. They serve as a safety net,
in case you accidentally do something stupid to brick your bootloader.  
To flash these, you will need to enter DFU mode.

#### Prusa Mini+
- TBC

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

- [Prusa Buddy Board - GitHub](https://github.com/prusa3d/Buddy-board-MINI-PCB/)

<br/>
