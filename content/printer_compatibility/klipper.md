---
weight: 201
title: "Klipper"
draft: false
toc: true
# description: "Example document nested inside multiple subfolders"
date: "2025-12-07T00:10:31+01:00"
lastmod: "2025-12-07T00:10:31+01:00"
tags: ["klipper", "compatibility"]
---

## Feature Compatibility

> Please note, not all configurations may be present in the Git repository at this time, as support is continuing to
develop.  
> In the near future, this page will reflect the current state of development.

> Below is a list of the current state of feature compatibility with the Prusa lineup, as of December 2025.

### Printers

| Feature              | Prusa MK3/S/+ | Prusa MK3.5/S | Prusa MK3.9/S | Prusa Mini/+ | Prusa MK4/S | Prusa Core One/+/L | Prusa XL                       | Prusa Pro HT90 |
|:---------------------|:--------------|:--------------|:--------------|:-------------|:------------|:-------------------|:-------------------------------|:---------------|
| Motion System        | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅                              | ❓              |
| Extruder             | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅                              | ❓              |
| Hotend Thermistor    | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅                              | ❓              |
| Heatbreak Thermistor | -             | ✅             | ✅             | -            | ✅           | ✅                  | ✅                              | ❓              |
| Bed Thermistor       | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅                              | ❓              |
| Filament Sensor      | ✅             | ❌             | ❌             | ❌            | ❌           | ❌                  | ❌                              | ❓              |
| Load Cell            | -             | -             | ✅             | -            | ✅           | ✅                  | ✅ Single Tool<br/>❌ Multi Tool | ❓              |
| Z Probing            | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅ Single Tool<br/>❌ Multi Tool | ❓              |
| Z Homing             | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅ Single Tool<br/>❌ Multi Tool | ❓              |
| Bed Mesh Calibration | ✅             | ✅             | ✅             | ✅            | ✅           | ✅                  | ✅ Single Tool<br/>❌ Multi Tool | ❓              |

---
### Multi-Material Unit

| Feature       | MMU2/S | MMU3 | Notes                                                                                                                                                                           |
|:--------------|:-------|:-----|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Control Board | ❌      | ❌    | The stock control board does not have enough EEPROM to hold a full installation of Klipper.<br/>Be advised, a slimline installation needs to be created for this board to work. |
| Idler         | ❌      | ❌    |                                                                                                                                                                                 |
| Pulley        | ❌      | ❌    |                                                                                                                                                                                 |
| Selector      | ❌      | ❌    |                                                                                                                                                                                 |
