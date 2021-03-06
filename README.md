## MAX72xx LED Matrix Library adapted for Mongoose OS

Not used as an integrated Mongoose OS library, ie: not in the `libs` section of mos.yml.

**WARNING** Hard coded for ESP32 hardware SPI.


Original README below:


# MAX72xx LED Matrix Display Library

The library implements functions that allow the MAX72xx to be used for LED matrices (64 individual LEDs), allowing the programmer to use the LED matrix as a pixel device, displaying graphics elements much like any other pixel addressable display.

In this scenario, it is convenient to abstract out the concept of the hardware device and create a uniform and consistent pixel address space, with the libraries determining device and device-element address. Similarly, control of the devices is uniform and abstracted to a system level.

The library still retains flexibility for device level control, should the developer require, through the use of overloaded class methods.

If you like and use this library please consider making a small donation using [PayPal](https://paypal.me/MajicDesigns/4USD)

[Library Documentation](https://majicdesigns.github.io/MD_MAX72XX/)
