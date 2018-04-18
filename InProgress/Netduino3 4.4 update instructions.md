# Netduino 3 Manual Firmware Update Instructions for .NET MF 4.4

## Downloads:
[.NET MicroFramework 4.4 RTW](https://github.com/NETMF/netmf-interpreter/releases/download/v4.4-RTW-20-Oct-2015/MicroFrameworkSDK.MSI)

Netduino 4.4 Visual Studio 2017 Extension (netmfvs15.zip)

Netduino 3 Firmware (should contain 3 files): 
- ER_CONFIG
- ER_FLASH
- TinyBooter.dfu

DfuSe from my.st.com (requires a free account)

## Steps

### Install software and extensions
- Install Visual Studio 2017 
- Install DfuSe
- Install NETMF 4.4 RTW
- Install netmfvs15 <- extention for VS2017

### Update N3 Bootloader driver
- Connect N3 in bootloader mode
- Open Device Manager
- Find **STM32 BOOTLOADER**
- Force-install 3.0.5 driver from SfuSe (included with installation)

### Erase N3
- Open DFU Tester
- Operation -> Erase (radio button on left)
- Tap Go button (below radio button)

### Flash Bootloader
- Open DfuSe Demo
- Tap bottom Choose... button (in Upgrade or Verify Action section)
- Select tinybooter.dfu from firmware download
- Tap Upgrade

### Flash Firmware
- Open .NET Micro Framework Deployment Tool
- Ensure device is selected
- Tap Browse ... in Image File section
- Select both firmware files (ER_CONFIG & ER_FLASH)
- Tap Deploy



