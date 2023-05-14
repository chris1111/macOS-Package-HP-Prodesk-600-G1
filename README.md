Update 14 May 2023 OpenCore-Package-0.9.3-V1

# macOS-Package-HP-Prodesk-600-G1

### SIP Security and Gatekeeper must be disable to using this Program!

![system16 copy](https://user-images.githubusercontent.com/6248794/136391545-6f86a804-d7c2-4f4c-bc25-87fb8583bbce.png)
#### Support Monterey 12, macOS Ventura 13 / Boot Windows 10, Windows 11 natively Use SSDT Patch


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
3. Integreted Video = Disabled (For Ventura 13)

## Note: Intel HD 4600 not working in macOS Ventura 13


- Download ➤ [OpenCore-Package-0.9.3-V1.zip](https://github.com/chris1111/macOS-Package-HP-Prodesk-600-G1/raw/main/OpenCore-Package-0.9.3-V1.pkg.zip)

### By installing this package it will install a specific EFI folder for the HP Prodesk 600 G1, so if you already have Open Core install make a backup of your EFI before using this program.

![ScreenPackage](https://user-images.githubusercontent.com/6248794/136392209-5d980241-3603-420b-b60e-24f60b99e322.png)

##### Credit:
- [acidanthera](https://github.com/acidanthera) OpenCore + kexts/Plugins
- [headkaze](https://github.com/headkaze) Hackintool
- [1alessandro1](https://github.com/1alessandro1/HP-Prodesk-600-G1-SFF-macOS) OpenCore-Package-0.8.4-V2 ➤ SSDT

