# XPS 13 9343 Kernel Package

This package currently reverts a patch that breaks the touchpad.  There is currently work being done by others to properly fix this issue for future kernel releases. A sound fix will be added when one is available.

## Not yet working

* sound
* multi-touch

## Installation Steps

    $ git clone https://github.com/soleblaze/linux-xps13-9343
    $ cd linux-xps13-9343
    $ makepkg -s
    $ sudo pacman -U *.pkg.tar.xz

Note: You will need to set your bootloader to use this kernel on boot.
