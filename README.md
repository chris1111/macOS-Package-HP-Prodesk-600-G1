# macOS-Package-HP-Prodesk-600-G1 

[![Github Actions](https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1/actions/workflows/Build.yml/badge.svg?branch=main)](https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1/actions)

### Site ➤ [macOS-Package-HP-Prodesk-600-G1](https://chris1111.github.io/macOS-Package-HP-Prodesk-600-G1/)
### SIP Security and Gatekeeper must be disable to using this Program!

![Demo](https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1/blob/main/Demo.png)

#### Support macOS Monterey 12, macOS Ventura 13, macOS Sonoma 14, macOS Sequoia 15, macOS Tahoe 26 / Boot Windows 10, Windows 11 natively

### Update 17 Nov 2025 Adapted for Tahoe 26. Update Update OpenCore 1.0.7 (REL-107-2025-11-17)
### Support  
- CPU: i5-4590 (3,30 GHz)
- Graphics: Intel HD 4600 / AMD Radeon Pro WX 4100 4 GB: 
- 16 Gig RAM  DDR3
- Disk Burning: HP DVD-RAM UJ8E1
- macOS Sonoma 14 / OpenCore 0.9.9
- PCIe SATA card: Marvell 88SE9128 StarTech PCI Express
- Broadcom Brcm43xx

### Bios setup:
1. use bios defaults
2. Storage = SATA Emulation > AHCI
3. Integreted Video = Disabled (For Ventura 13, Sonoma 14, Sequoia 15)

### Note: Intel HD 4600 not working in macOS Ventura 13, macOS Sonoma 14, macOS Sequoia 15; You must use [OCLP](https://github.com/dortania/OpenCore-Legacy-Patcher/) to acheive this.

## How to download and Build Package ⬇︎

- Prerequisite: [Git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)- or Command Line Tools (CLT) for Xcode (from `xcode-select --install` or [Developer Apple Command Line Tools](https://developer.apple.com/download/all/)

- [x] `Command build`

`git clone https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1.git && cd macOS-Package-HP-Prodesk-600-G1 && cd OpenCorePackageProdesk && ./Build-Package`


### By installing this package it will install a specific EFI folder for the HP Prodesk 600 G1, so if you already have Open Core install make a backup of your EFI before using this program.

![ScreenPackage](https://user-images.githubusercontent.com/6248794/136392209-5d980241-3603-420b-b60e-24f60b99e322.png)

##### Credit:
- [acidanthera](https://github.com/acidanthera) OpenCore + kexts/Plugins
- [headkaze](https://github.com/headkaze) Hackintool
- [chris1111](https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1) OpenCore-Package-HP-Prodesk-600-G1
  


