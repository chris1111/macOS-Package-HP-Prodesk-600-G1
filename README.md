Update 29 Dec 2023 OpenCore-Package-0.9.8-V2
- Fix Sleep / wake Sonoma 14, Fix Boot Windows.
- Update OpenCore 0.9.8

# macOS-Package-HP-Prodesk-600-G1

### SIP Security and Gatekeeper must be disable to using this Program!

![Demo](https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1/blob/main/Demo.png)

#### Support Monterey 12, macOS Ventura 13, macOS Sonoma 14 / Boot Windows 10, Windows 11 natively


### Support  
- CPU: i5-4590 (3,30 GHz)
- Graphics: Intel HD 4600 / AMD Radeon Pro WX 4100 4 GB: 
- 16 Gig RAM  DDR3
- Disk Burning: HP DVD-RAM UJ8E1
- macOS Ventura 13 / Open Core 0.8.4
- PCIe SATA card: Marvell 88SE9128 StarTech PCI Express
- Broadcom Brcm43xx

### Bios setup:
1. use bios defaults
2. Storage = SATA Emulation > AHCI
3. Integreted Video = Disabled (For Ventura 13, Sonoma 14)

## Note: Intel HD 4600 not working in macOS Ventura 13, macOS Sonoma 14

## How to download and Build Package ⬇︎
Note: Using the Package for macOS Sonoma 14
- Rename `config.plist` to `config-Ventura.plist` Rename `config-Sonoma.plist` to `config.plist`

- Prerequisite: [Git installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)- or Command Line Tools (CLT) for Xcode (from `xcode-select --install` or [Developer Apple Command Line Tools](https://developer.apple.com/download/all/)

- [x] `Command build`
```bash

git clone https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1.git
cd macOS-Package-HP-Prodesk-600-G1
cd OpenCorePackageProdesk
./Build-Package

```


### By installing this package it will install a specific EFI folder for the HP Prodesk 600 G1, so if you already have Open Core install make a backup of your EFI before using this program.

![ScreenPackage](https://user-images.githubusercontent.com/6248794/136392209-5d980241-3603-420b-b60e-24f60b99e322.png)

##### Credit:
- [acidanthera](https://github.com/acidanthera) OpenCore + kexts/Plugins
- [headkaze](https://github.com/headkaze) Hackintool
- [chris1111](https://github.com/chris1111) OpenCore-Package-0.9.4-V1 ➤ DSDT

