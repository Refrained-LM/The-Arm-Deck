Use Megajoy-on-uno.ino and Megahoy.h in the Ardunio IDE and flash normally
Then reboot the device and put it in DFU mode and flash Megajoy.hex with dfu-programmer.
Reboot and it should show up as a game controller.


Put device in DFU mode and flash with Arduino-usbserial-uno.hex can be tricky I recommand another uno in ISP moden to reflash the bootloader in Ardunio IDE again can be tricky I added https://github.com/NicoHood/HoodLoader2 Files flash boot loader easier if needing to put the uno back to stock.
