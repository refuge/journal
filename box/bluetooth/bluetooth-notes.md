# A few things about bluetooth and linux

## Good pointers

+ http://askubuntu.com/questions/187092/bluetooth-from-the-command-line-in-12-04
+ [pretty cool usb dongle](http://www.amazon.com/Plugable-Bluetooth-Adapter-Windows-Compatible/dp/B009ZIILLI/)
+ http://openelec.tv/forum/104-bluetooth-remotes/20257-connecting-bluetooth-devices-and-bd-remote-in-the-latest-development-builds
+ Bluetooth 4.1 spec: https://www.bluetooth.org/en-us/specification/adopted-specifications

+ http://stackoverflow.com/questions/10502645/serving-a-local-website-via-bluetooth-to-a-cellphone-without-using-the-internet
+ http://developer.android.com/reference/android/bluetooth/BluetoothSocket.html#connect()
+ http://stackoverflow.com/questions/3312914/setting-up-a-pc-bluetooth-server-for-android
+ RFCOMM: http://people.csail.mit.edu/albert/bluez-intro/x502.html
+ Setting up a pin with bluez: http://www.linuxquestions.org/questions/linux-wireless-networking-41/setting-up-bluez-with-a-passkey-pin-to-be-used-as-headset-for-iphone-816003/
+ Debian and Bluetooth: https://wiki.debian.org/BluetoothUser

+ Bluetooth class navigator (very useful): http://bluetooth-pentest.narod.ru/software/bluetooth_class_of_device-service_generator.html
+ Bluetooth services: http://bluetooth-pentest.narod.ru/doc/assigned_numbers_-_service_discovery.html

## Very interesting implementation in erlang:

+ https://github.com/drimtajm/bluetooth (see her conf here: https://www.youtube.com/watch?v=kbqv_PQLcYM)

## On Ubuntu 12.04

I tried several things on ubuntu 12.04 on the udoo quad, and a basic usb dongle.
Everything is done through hciconfig and hcitool.

It seems very interesting to install the package bluetool-tools (bt-*).

The main thing is bluetoothd which is configured with a bunch of files in /etc/bluetooth.

