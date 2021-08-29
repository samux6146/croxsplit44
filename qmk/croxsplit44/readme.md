croxsplit44
![davanti](https://user-images.githubusercontent.com/41386727/131268038-801cb316-7bb1-486d-8432-be5412ddc31b.jpg)

A 3d printed 44 key handwired split keyboard
thanks to ak666666 for the base case layout : https://www.thingiverse.com/thing:4146704

Keyboard Maintainer: https://github.com/Samux6146
Hardware Supported: handwired, teensy ++ 2.0

Make example:
make handwiered/croxsplit44:default
or if you want to use via:
make handwiered/croxsplit44:default

Bootloader
Enter the bootloader in 3 ways:

Bootmagic reset: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
Physical reset button: Briefly press the button on the back of the PCB - some may have pads you must short instead
Keycode in layout: Press the key mapped to RESET if it is available
