# A few things about bluetooth and linux

## Good pointers

+ http://askubuntu.com/questions/187092/bluetooth-from-the-command-line-in-12-04
+ [pretty cool usb dongle](http://www.amazon.com/Plugable-Bluetooth-Adapter-Windows-Compatible/dp/B009ZIILLI/)
+ http://openelec.tv/forum/104-bluetooth-remotes/20257-connecting-bluetooth-devices-and-bd-remote-in-the-latest-development-builds

## On Ubuntu 12.04

I tried several things on ubuntu 12.04 on the udoo quad, and a basic usb dongle.
Everything is done through hciconfig and hcitool.

It seems very interesting to install the package bluetool-tools (bt-*).

The main thing is bluetoothd which is configured with a bunch of files in /etc/bluetooth.

