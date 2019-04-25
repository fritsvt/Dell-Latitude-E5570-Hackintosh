# Dell-Latitude-E5570-Hackintosh

Run Mac OS Mojave on a Dell Latitude e5570

This guide and anything in the repo comes with no warranty. Use at your own
risk! I am not responsible if you get fired because your hackingtosh is broken.

Big thanks to [osxlatitude.com](https://osxlatitude.com) it wouldn't be
possible without the help of [Jake
Lo](https://osxlatitude.com/profile/1549-jake-lo/)

![about mac](https://i.boring.host/YVRGdu8.png)
![laptop](https://i.boring.host/YIPaJ5w.jpg)

## What works?

I have changed the wifi card to a DW1830. With that said most stuff should work on this laptop (I currently use it as daily driver). Except for the following:
- Bluetooth (fixable but I just don't use it)
- Touchpad gestures
- Finder Sensor, smart card reader if you have one
- SD Card reader

## Installation

Get Mac OS running on your laptop

- Follow the Vanilla guide in the sidebar to make a bootable usb with Mojave
  [r/hackintosh](https://reddit.com/r/hackingtosh)
- Mount the EFI partition on the USB with a tool like [clover configurator](https://mackie100projects.altervista.org/download-clover-configurator/)
- Replace the Clover folder in the EFI partition with the contents of [clover.zip](CLOVER.zip)
- Unmount the EFI partition
- Boot the USB on your Latitude E5570 and install Mac OS on your laptop
- After the installation finished boot from your USB again and select the drive
  it has installed to.
- Get [clover configurator](https://mackie100projects.altervista.org/download-clover-configurator/)
  on your new mac
- Now mount the EFI partition of your boot drive
- Replace the Clover folder in the EFI partition with the contents of [clover.zip](CLOVER.zip)
- Unmount the EFI partition

Fix keyboard shortcuts
- Download and install [Karabiner Elements](https://pqrs.org/osx/karabiner/)
- Download [karabiner.json](karabiner.json) found in [this guide from osxlatitude](https://osxlatitude.com/forums/topic/9179-dell-latitude-e7x70-clover-uefi-only/)
- Copy karabiner.json to ~/.config/Karabiner
- You can now use F11 & F12 for brightness

Get smooth scrolling
- Download and install [MOS](https://mos.caldis.me)

Thanks for reading. Good luck installing!
