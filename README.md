# Matrix Bootloader

This repo is a fork of [TinyUF2](https://github.com/adafruit/tinyuf2) for 203 Matrix Devices

Compared to the origonal bootloader, this fork added proper multi RGB pixel support, fastboot, device specific animations, and some Matrix specific functions.


## Build for Matrix:

  > run the export bat come with esp-idf first

    cd ports\espressif
    make BOARD=matrix_block6_prototype1 build

## Flash
  > Matrix has to be in boot mode (boot pin shorted to ground) and connected to PC via ttl-usb convertpr


    make BOARD=matrix_block6_prototype1 build flash