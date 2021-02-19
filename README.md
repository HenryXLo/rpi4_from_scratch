# rpi4_from_scratch

Hi All, my nams is Henry Lo and I'm an embedded engineer and a enthusiast of embedded system development. Anything about arm, linux, kernel, drivers, OS, different RISC chipsets would be interesting me.

In this project, I would like to study embedded development by exploiting the Raspberry Pi 4 model B SBC which is a very handy SBC. It equips with the ARMv8 Quad-core A72 64-bit SOC (BCM2711) which is very powerful and it's very convenient to study embedded programming. Basically, I would go thorough the process in different areas.

Linux related:
a.) porting a embedded linux to RPi4 - go thru' Linux From Scratch
b.) implement a basic character driver on RPi4
c.) implement a I2C driver to access EEPROM on RPi4 (with example to wire atmel 24C08 eeprom to RPi4 board)

Barematel programming on RPi4
a.) setup programming environment (i.e. prepare USB-serial programming interface, setup IDE)
b.) study basic RPi4 gpio control
c.) further study? (TBC)

OS basic:
a.) study boot sequence (e.g. study assembly in boot.s)
b.) write a simple monolithic OS kernel
    - (TBC)
c.) add simple drivers to peripherals:
    i) gpio to control LED lights
    ii) write a I2C driver from scratch to access EEPROM read/write operations.
d.) furher study? (TBC)
