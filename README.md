# OpenCore-Lenovo-ThinkPad-L470
This repository contains OpenCore 1.0.5 configured for the Lenovo ThinkPad L470 W10DG laptop (i5-6200U with HD 520 without WWAN). Tested with macOS Tahoe Beta 3 on USB SSD (may require changing boot scan policy for other devices). Every piece of my hardware works except sound, because of lack of AppleHDA.kext in latest macOS 26 as of July 2025, Wi-Fi works with itlwm.kext and HeliPort app, iServices weren't tested. CPUFriend is preconfigured by me, but you might need to remove it (or reconfigure for your own needs). Trackpad uses VoodooRMI (yay responsive gestures), if trackpad doesnt work for you, remove VoodooRMI.kext and VoodooSMBus.kext, then enable VoodooInput.kext plugin from VoodooPS2Controller.kext. Remember to change your SMBIOS if you plan to use this repo. Includes OpenCanopy (graphical bootloader).

# Thanks to

[allyssonmoscoso](https://github.com/allyssonmoscoso/ThinkPadL470-OpenCoreEFI) (Original repository)