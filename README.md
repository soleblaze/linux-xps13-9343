# XPS 13 9343 Kernel Package

This package currently patches a pre 4.1-rc1 git revision in order to get sound working correctly in i2s mode.  SPX Mux needs to be set to Front and SP0 needs to be unmuted in order for sound to work properly.

This also includes some AHCI, usb hub, and PSR patches in order to lower power
usage.

## Not yet working

* palm detection

## Installation Steps

    git clone https://github.com/soleblaze/linux-xps13-9343 -b testing
    cd linux-xps13-9343
    makepkg -s
    sudo pacman -U *.pkg.tar.xz

Note: You will need to set your bootloader to use this kernel on boot.
