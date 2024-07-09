**You probably reached this page by watching one of my [Ergo Split Keyb Videos](https://www.youtube.com/playlist?list=PL1E2ddJCbc13DvCGYXX9jVVX1BqNGKE5D).**

This repository hosts my zmk-configs as seen on the YouTube videos linked above.

Additionally, this repository contains alternative configurations meant to be used with an extra controller acting as a dongle. Pease refer to the [Dongle Flashing](https://github.com/eigatech/zmk-config#dongle-flashing) chapter for instructions.

### Corne

- [Corne](https://github.com/eigatech/zmk-config/tree/corne)
- [Corne Dongle](https://github.com/eigatech/zmk-config/tree/corne-dongle)

### Charybdis

- [Charybdis](https://github.com/eigatech/zmk-config/tree/charybdis-3.5)
- [Charybdis Dongle](https://github.com/eigatech/zmk-config/tree/charybdis-dongle)

### TOTEM

- [TOTEM](https://github.com/eigatech/zmk-config/tree/totem)
- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle)

### Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers housed in a nifty 3D printed [case](https://www.printables.com/model/522586-seeed-xiao-ble-case).

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.

*When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!*

### Notes

The configurations above are meant to be used with builds that are identical to the ones featured in the videos, otherwise they should be used as reference only.

### ZMK Modules used

[zmk-split-peripheral-input-relay](https://github.com/badjeff/zmk-split-peripheral-input-relay)

[zmk-input-behavior-listener](https://github.com/badjeff/zmk-input-behavior-listener)

[zmk-pmw3610-driver](https://github.com/badjeff/zmk-pmw3610-driver)
