
## LegionY545_BigSur

![My Big Sur](https://github.com/indowebdeveloper/LegionY545_BigSur/blob/main/about.png)

## What is this ??
This is my first release of EFI for my Hackintosh Legion Y545 on Big Sur 11.0.1
The purpose of this article is to make LENOVO LEGION Y545 series laptops use MacOS as perfectly as possible.

## what do you need

-   Downloaded MacOS image (macOS Big Sur image installation)
-   16GB U Disk

## BIOS ensures settings

-   Enable UEFI boot.
-   Disable secure boot.
-   The SATA mode is set to AHCI.

## Functions that work normally

-   UEFI boot via OC
-   Support any version system OTA upgrade to the latest system
-   Built-in keyboard and numeric keyboard
-   Primitive USB3.0 / USB2.0
-   AppleHDA native audio, including headphones
-   Built-in camera
-   Native power management
-   Battery status
-   Backlight control
-   Backlit keyboard
-   Nuclear display driver (independent display has been hotpatch blocked)
-   Wired Ethernet card
-   The Mac App Store works normally
-   CPU frequency conversion
-   Sleep wake (mouse, keyboard, power button wake up are all normal)
-   Built-in Wireless network & Bluetooth
-   touchpad
-   Onboard (wired/wireless)
-   iMessage/FaceTime

## Unusable function

-   HDMI because the HDMI port is connected to a disabled Nvidia card

## Optimization command

```
sudo sh -c "$(curl -fsSL https://gitee.com/xiaoMGit/Y7000Series_Hackintosh_Fix/raw/master/Script/Optimize.sh)"

```

## Wanna give me a cup of coffee ??

You may send me bucks using paypal
https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=adw.indoweb@gmail.com&lc=GB&item_name=Legion%20Hackintosh&currency_code=GBP&no_note=0&bn=PP-DonationsBF:btn_donateCC_LG.gif:NonHostedGuest
