# ThinkPad-X380-Hackintosh

Working:

* Keyboard (VoodooPS2Controller).
* Multitouch trackpad (VoodooSMBus) with native macOS gestures, trackpoint.
* HiDPI display.
* Audio.
* HDMI (w/ audio).
* graphics, power management, sleep, undervolting ([https://github.com/sicreative/VoltageShift](https://github.com/sicreative/VoltageShift))
* USB ports.
* Bluetooth.
* 2nd NVMe in WWAN slot.
* Thunderbolt 3/USB-C hotplug, display out over USB-C
* Brightness keys

Needs some work:

* microSD reader (works, but stops working after sleep and requires reboot). Is there anything better than sinetek-rtsx.kext?
* Touchscreen (pen recognized, but no touch; TouchBase UPDD works, but I don't own the full version). Let me know if you know how to get VoodooI2C working for HID-USB in parallel of VoodooSMBus

Does not work

* Intel WiFi (I use a USB dongle while waiting for an Intel driver or supported card).
