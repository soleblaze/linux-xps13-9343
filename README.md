# XPS 13 9343 Kernel Package

This package currently patches 4.0-rc5 in order to get sound working correctly in i2s mode.  SPX Mux needs to be set to Front in order for sound to work properly.

## Not yet working

* palm detection

## Installation Steps

    git clone https://github.com/soleblaze/linux-xps13-9343
    cd linux-xps13-9343
    makepkg -s
    sudo pacman -U *.pkg.tar.xz

Note: You will need to set your bootloader to use this kernel on boot.
