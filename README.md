![Twitter Follow](https://img.shields.io/twitter/follow/fgvilches?style=social)

![GitHub followers](https://img.shields.io/github/followers/fgvilches?style=social)

# ASUS VIVOBOOK X420 HACKINTOSH

-----
Run macOS on your Asus X420

**Works fine on Mojave / Catalina** 

## Contents

- [Configuration](#configuration)
- [Current Status](#current-status)
  - [Clover](#clover)
  - [OpenCore](#opencore)
- [Installation](#installation)
  - [First-time installation](#first-time-installation)
  - [Build](#build)
  - [Upgrade](#upgrade)
- [Improvements](#improvements)
- [FAQ](#faq)
- [Changelog](#changelog)
- [A reward](#a-reward)
- [Credits](#credits)
- [Support and discussion](#support-and-discussion)

| Specifications      | Detail                                     |
| ------------------- | -------------------------------------------|
| Computer model      | Asus Vivobook X420UA                       |
| Processor           | Intel Core i5-7200U Processor              |
| Memory              | 4GB Samsung DDR4L (Soldered) 2133MHz       |
| Hard Disk           | Sandisk 128GB SSD SD9SN8W128G1102          |
| Integrated Graphics | Intel HD Graphics 620                      |
| Sound Card          | Realtek ALC256                             |
| Webcam              | UVC HD Webcam                              |
| Wireless Card       | Intel Wireless 8265 (Replaced with DW1820a)|
| SD Card Reader      | Realtek RTS5129/RTS5250S                   |


## Current Status

- **Intel Wi-Fi (Intel Wireless 8265)** could work by additional configurations (see [this pdf for more details](https://github.com/fgvilches/ASUS-VIVOBOOK-X420-HACKINTOSH/blob/master/Docs/Drive-Native-Intel-Wireless-Card.pdf))
  - I've remplaced it with a DW1820a (hw mod needed)

- **Realtek USB SD Card Reader** It works on mojave but is not working on catalina

- **UVC HD Webcam** Is not working
  - I've tried for months to get it working without result.
  
- **Sleepmode** Is working partially
  - It works. When you close the lid, enters in sleepmode but when you open it to return, the notebook reboots.
  
- Everything else works well


### Clover
- Support macOS10.13 ~ macOS10.15.6, **Currently working on Big Sur Support+**
- Should Clean NVRAM after using OpenCore
  - Press `Fn+F11` in Clover boot page

### OpenCore
- I don't have an opencore build currently. **I'm working on one**


## Installation

### First-time installation
- I recommend installing using a pre-made Oralira dmg (links), after installing replace update clover bootloader and replace the EFI folder with one of the [releases](https://github.com/daliansky/XiaoMi-Pro-Hackintosh/releases) page.





