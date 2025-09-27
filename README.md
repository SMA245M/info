# 📦 Samsung A24 Dump (a24ub-user 15 AP3A.240905.015.A2 A245MUBSADYG1)

This repository contains extracted and unpacked firmware information for the **Samsung Galaxy A24** (codename: `a24`).  
It includes boot/recovery image details, vendor boot extraction, and device properties.

---

## 📑 Device Information

| Field            | Value                                                                 |
|------------------|-----------------------------------------------------------------------|
| **Manufacturer** | samsung                                                               |
| **Platform**     | mt6789                                                                |
| **Codename**     | a24                                                                   |
| **Brand**        | samsung                                                               |
| **Flavor**       | a24ub-user                                                            |
| **Release**      | Android 15                                                            |
| **Kernel**       | 5.10.226                                                              |
| **Build ID**     | AP3A.240905.015.A2                                                    |
| **Incremental**  | A245MUBSADYG1                                                         |
| **Tags**         | release-keys                                                          |
| **CPU Abilist**  | arm64-v8a, armeabi-v7a, armeabi                                       |
| **A/B Device**   | false                                                                 |
| **Treble**       | true                                                                  |
| **Locale**       | en-GB                                                                 |
| **Screen Density** | undefined                                                           |
| **Fingerprint**  | samsung/a24ub/a24:12/SP1A.210812.016/A245MUBSADYG1:user/release-keys  |
| **OTA Version**  | –                                                                     |
| **Branch**       | a24ub-user-15-AP3A.240905.015.A2-A245MUBSADYG1-release-keys           |
| **Repo**         | `samsung_a24_dump`                                                    |

---

## 🗂 Boot Image Details

### 1. First Boot Image Extraction
- **Board**: `N2 loop.max_part`  
- **Page Size**: `861090870`  
- **Second Size**: `9676805`  
- **Base**: `0xffff9000`  
- **Kernel Offset**: `0x00008000`  
- **Ramdisk Offset**: `0x66f07000`  
- **DTB Image**: `dtb.img`  
- **DTB Size**: `1311912748`  
- **DTB Offset**: `0x00007000`  
- **Second Offset**: `0x746fdf62`  
- **Tags Offset**: `0x3d74e06f`  
- **Cmdline**: `=7`
---

### 2. Recovery Image Extraction
- **Board**: `SRPVL01A010`  
- **Kernel**: `kernel`  
- **Ramdisk**: ramdisk *(lz4 format)*  
- **Page Size**: `4096`  
- **Kernel Size**: `18832483`  
- **Ramdisk Size**: `27496976`  
- **Base**: `0x3fff8000`  
- **Kernel Offset**: `0x00008000`  
- **Ramdisk Offset**: `0x26f08000`  
- **Boot Header Version**: `2`  
- **DTBO**: `dtbo.img`  
- **DTBO Size**: `203962`  
- **DTBO Offset**: `0xc2c39000`  
- **DTB Image**: `dtb.img`  
- **DTB Size**: `188009`  
- **Tags Offset**: `0x07c88000`  
- **Cmdline**: `bootopt=64S3,32N2,64N2 loop.max_part=7`  

