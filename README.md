TinyBasic Plus
==============
This is the version with VGAX and PS2 Keyboard support. I will 
modify this program to add more features like maybe graphics 
commands or just some other random thing that I come up with.
This uses pin 10 for rx and pin 11 for tx. This was modified
to work with my arduino leonardo, it will work with most of
the other common arduino platforms.

Links to the needed libraries
==============
https://github.com/yosemitebandit/PS2Keyboard for the arduino leonardo

https://github.com/PaulStoffregen/PS2Keyboard for the platforms listed below
Arduino Uno:  2, 3
Arduino Due:  All pins, except 13 (LED)
Arduino Mega: 2, 3, 18, 19, 20, 21
Teensy 3.0:   All pins, except 13 (LED)
Teensy 2.0:   5, 6, 7, 8
Teensy 1.0:   0, 1, 2, 3, 4, 6, 7, 16
Teensy++ 2.0: 0, 1, 2, 3, 18, 19, 36, 37
Teensy++ 1.0: 0, 1, 2, 3, 18, 19, 36, 37
Sanguino:     2, 10, 11

https://github.com/smaffer/vgax

The project guide for the platforms listed above 
accept for the leonardo specific libraries.
