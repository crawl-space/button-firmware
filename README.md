# Button Firmware

That was trivial

## Flashing

Begin by compiling everything, then flashing the bootloader with your
programmer of choice.

```bash
# start by compiling everything
make
# set the fuse bits
make fuse
# flash the bootloader
make flash
```

Now you can program via a USB connection.

```
make flash-firmware
```

## References

Based on the great work of others:
 - usb: [v-usb](http://www.obdev.at/products/vusb/index.html)
 - bootloader: [micronuleus-t85](https://github.com/Bluebie/micronucleus-t85)
 - Based on [nespad](https://github.com/jbowes/nespad)
