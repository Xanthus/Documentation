---
layout: Netduino
title: Windows Installation
subtitle: Installing the .NET MicroFramework and Netduino SDKs on Visual Studio 2017
---

# Prerequisites
Visual Studio 2017 supports version 4.4 of the .NET Micro Framework.

You'll need to install the preview Netduino 4.4 firmware [avaliable here](https://wildernesslabs.co/downloads/xxxxxxxxxxxx).
Currently the base Netduino 2 and Netduino 3 are supported. (Firmware for ethernet and WiFi versions coming soon)

## Note
Visual Studio 2017 and Visual Studio 2015 support side-by-side installation and can both be installed on the same Windows PC.


# Instructions

Download and install the following:

1. [.NET Micro Framework (.NETMF) v4.4.0 SDK](https://github.com/NETMF/netmf-interpreter/releases/tag/v4.4-RTW-20-Oct-2015)
2. NETMF Plugin for [Visual Studio 2017](https://www.wildernesslabs.co/downloads?f=/NETMF_SDK/netmfvs15xxxxxxxxxxxxxxxxxxx.vsix)
3. [Preview 4.4 Netduino SDK](https://www.wildernesslabs.co/downloads?f=/Netduino_SDK/netduinosdk_v44.exe)

# Reverting to Visual Studio 2015 and v4.3

If you want to return to the latest stable 4.3 release, follow the steps below:

1. [Flash](http://developer.wildernesslabs.co/Netduino/About/Updating_Firmware/#windows) the latest 4.3 release firmware to your Netduino
2. Uninstall the 4.4 Netduino SDK
3. Follow the 4.3 [installation instructions](http://developer.wildernesslabs.co/Netduino/Getting_Started/Installation/Windows/)

