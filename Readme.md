# 24-04-2024
### There is a possiblity of having network connection over ethernet
* Beagle bone black has this.
* Similar but different to usb tethering
    * usb tethering is to share internet over usb
* How to share wifi internet over ethernet
    * https://unix.stackexchange.com/questions/575178/sharing-wifi-internet-through-ethernet-interface

### using old user space interface before linux 4.8 to manage GPI0
Basic GPIO operations that can be performed via this interface:

* Export a GPIO via /sys/class/gpio/export
* Configure the GPIO direction (input/output) via: /sys/class/gpio/gpioX/direction
* Read/write GPIO value via /sys/class/gpio/gpioX/value



