# **SafetyPatcher**
## Description
Fixes safetynet basicIntegrity on most devices, after you've applied magiskhide
## Changelog
- A1 - Initial alpha
- v1 - Includes fixes for OP3 and other devices with messed up cases in the bootloader
## Requirements
- No phh software, including GSI. It will be detected by safetynet. IF you have a GSI, you must use the MagiskHide Props Config to change your device fingerprint.
- Magisk
- Magisk Hide
- Magisk Manager for TWRP Recovery (for when things go wrong)
## Instructions
1. Flash in Magisk Manager
2. Reboot
3. Comment on XDA to share your experience

Or to use without Magisk...

1. Enable ADB.
3. Run `adb shell sed 's/ORANGE/GREEN/i' /proc/cmdline > /data/local/tmp/cmdline` from computer with connected and authorized ADB/USB
4. `adb shell mount -o bind /data/local/tmp/cmdline /proc/cmdline` from computer with connected and authorized ADB/USB
5. Comment on XDA to share your experience
## Links
[Module XDA Forum Thread](https://forum.xda-developers.com/apps/magisk/module-safetypatcher-t3809879 "Module official XDA thread")

[Latest stable Magisk](http://www.tiny.cc/latestmagisk) or Beta if you want
