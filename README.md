Example project for using SDMMC with Zephyr in STM32H7
=====================================================
Jackie Yang <jackie@skywalk.dev>
-----------------------------------------------------

This project is an example of using SDMMC with Zephyr in STM32H7.

The keys to make it work are:
* Enable SDMMC in device tree
* Configure the clock source for SDMMC
* Format the SD card with *MBR* partition table and *FAT32* file system