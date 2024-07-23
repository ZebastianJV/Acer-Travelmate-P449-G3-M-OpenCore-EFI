# Acer-Travelmate-P449-G3-M-OpenCore-EFI
This is an EFI folder I have for the Acer P449-G3-M
![IMG_20240723_105430](https://github.com/user-attachments/assets/b50c4b27-0ca5-4f79-b240-63e9f4437f4e)
> [!CAUTION]
> This is **ONLY** for macOS Sonoma 14.4.1 so stuff **COULD** break when used with a different macOS version.
> [!NOTE]
> OpenCore version used is 0.9.1.
### Legend:
✅ Working
❓ Untested
❌ Not working
## Specs
| Component Type | What is it |
| ------------- | ------------- |
| CPU | Intel Core i5-8250U |
| GPU | Intel UHD 620 |
| RAM | 4GB soldered 2400 mhz ram + 8GBDDR4 3200Mhz ram (dual channel apparently) |
| CPU Codename | Kabylake-R |
| Screen | 1366x768 60hz |
| Wi-Fi Card | Intel Dual-Band Wireless AC 8260 |
| Ethernet Card | Intel I219 LM |
| OS | macOS Sonoma 14.4.1 |

[X] Wi-Fi (it works but it sometimes casually kicks you out and gives you an error message of you saying you tried but you can't do shit/
[X] Bluetooth
[X] Keyboard
[X] Brightness + brightness keys
[X] Charging
[X] Sleep (**DO NOT PRESS FN+F4 YOU WILL REGRET IT**) (lid closing does work if you are wondering)
[X] Battery Indicator + Percentage
[X] Graphics Acceleration (Intel UHD 620)
[X] All USB ports (including the USB-C port)
[X] SD Card Reader
[X] Function keys (F3 for network is buggy as hell but I never seem to get it to work cause it crashes my Wi-Fi sometimes, F4 does sleep the laptop except indefinitely, F5 opens pinned messages on Discord???, F6 turns on and off the display so your mates won't see how much you are watching po-, F7 turns off the touchpad, F8 is a mute volume key, F9 is turning on and of the keyboard backlight if you have that. F11/NumLock doesn't work. F12/ScrollLock doesn't work cause macOS does not support it. The media buttons on the right all work. The brightness and volume buttons on the shitty arrow keys do work as well.
[X] Headphone jack (i swear to fucking god apple if you goddamn remove support for it...)

❓ HDMI
❓ VGA (most likely it doesn't work because macOS doesn't support VGA anymore)
❓ Smart Card Reader (how the hell am I supposed to test this???)

[ ] Drop detection (like you would drop your laptop)
[ ] Fingerprint Scanner (no Touch ID emulation for any device with a fingerprint scanner at least for now)
[ ] Touchpad (needs boot arguments for it to **semi** work. The trackpad works temporarily. This should not be used as a boot argument as some will say it would cause heat and poor battery life on the laptop (working on the fix with GPIO pinning. Also left click on the touchpad barely works and the right click on the touchpad doesn't work at all... Wow so sad...)
[ ] AirDrop (barely fucking works it's just stupid. My iPhone won't detect the laptop and the laptop would detect the iPhone but the AirDrop on the laptop would say "Declined" whenever I try to send something. Just don't use it..

