# OpenCore-Lenovo-ThinkPad-L470
This repository contains OpenCore 1.0.0 with the required configuration for the Lenovo ThinkPad L470 laptop (i5-6200U with HD 520 without WWAN). Tested on macOS Sonoma 14.5 (June 2024) with SSD to USB (may require changing boot scan policy for other devices). Every piece of this hardware runs on macOS except the mini DP and VGA ports, the minijack has some sound channel issues, the Wi-Fi card is controlled by AirPort, and macOS can install OTA updates. Includes OpenCanopy (graphical bootloader) and USBMap (except USB in WWAN slot). The SMBIOS used is not adapted to the hardware, but to the latest macOS.

EFI/OC/Resources is not present - you have to get it from OpenCore GitHub repo
