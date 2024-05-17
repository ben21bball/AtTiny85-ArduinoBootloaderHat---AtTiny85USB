# AtTiny85-ArduinoBootloaderHat---AtTiny85USB
Want to set up an ATTiny85 as quickly as possible with a hot-swappable Arduino Uno R3 hat and USB adapter PCBs? Look no further!

This repository contains a project for an Arduino hat PCB for downloading a bootloader onto an ATtiny85 microcontroller and a PCB-based USB device for directly sending code to the ATtiny85. All PCB designs were intended to keep traces to one side of a PCB to enable the greatest number of tinkerers to recreate this to save them time with the ATtiny85 boot loading and programming. Hopefully this saves you time and money when making circuits to use the ATtiny85 with the Arduino IDE.

(This is for people who plan to make many ATTiny85-based devices and/or do not want their chip permanently soldered to an ugly USB board after programming.)

This is heavily inspired by the following links: https://circuitdigest.com/microcontroller-projects/attiny85-ic-programming-through-usb-using-digispark-bootloader https://circuitdiagrams.in/program-attiny85-microcontroller-using-usb/

Credit to the original tinkerers for coming up with these solutions or modifying them. I took issue with some of the diagrams in both of these links, as well as wanting to make a compact and open-source design. The circuit diagram for the USB device and the PCB layouts were designed in KiCAD. I will be adding a 3D printed enclosure for the USB device and the files will be added eventually.

https://resources.altium.com/p/how-design-custom-arduino-shield-board This is a link for the dimensions of a couple of Arduino boards, if you would like to design your own, this is where I started.

![image](https://github.com/ben21bball/AtTiny85-ArduinoBootloaderHat---AtTiny85USB/assets/112023334/f7e1d379-1b42-47ff-b557-563ba8f18d75)
Arduino Hat

![image](https://github.com/ben21bball/AtTiny85-ArduinoBootloaderHat---AtTiny85USB/assets/112023334/f3731a87-6a1e-4b01-a6b5-1ff72e8cb2b4)
USB Board
