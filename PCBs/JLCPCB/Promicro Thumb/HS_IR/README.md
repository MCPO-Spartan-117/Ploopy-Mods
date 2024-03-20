# Promicro Thumb-HS_IR
## WARNING, THIS BOARD IS MEANT FOR A 3.3V BOARD, THE SENSOR WON'T WORK AS IT ONLY HAS A REGULATOR FOR 3.3V to 1.8V FOR THE LED, NOT THE SENSOR'S 3.3V!!!

This PCB is designed to offload all the processing to a 3.3V Promicro sized/pinout board, so we can work with a 2 layer board and we can replace the processing board with a better/more functioning one if we want to.  
We intentionally didn't use the USB VBUS directly for components as we wanted to be able to support wireless [ZMK](https://zmk.dev) boards and we have a place where you can install a battery and switch.

These boards don't use a ESD component as it's on the MCU board.
