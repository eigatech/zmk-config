# bazantj's zmk-config
Based on fantastic [eigatech/zmk-config](https://github.com/eigatech/zmk-config).

My personal ZMK keymap config for TOTEM keyboard with dongle. Only the dongle branch is updated.

## TOTEM

- [TOTEM](https://github.com/eigatech/zmk-config/tree/totem)
- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle)
- [TOTEM Prospector](https://github.com/eigatech/zmk-config/tree/totem-prospector)

## Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers housed in a nifty 3D printed [case](https://www.printables.com/model/522586-seeed-xiao-ble-case).

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.

> [!WARNING]  
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!

## ZMK Keymap Editor

Nick Coutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a user-friendly, browser-based WYSIWYG app designed to make editing your keymap file easier. It supports conditional layers, behaviors, combo and macro editing, rotary encoders, and more.

## How to build 
- Build guide: https://github.com/GEIGEIGEIST/TOTEM/blob/main/docs/buildguide.md
- Video 1: https://www.youtube.com/watch?v=YwsutNf1WRA&t=143s

## Battery
https://github.com/itouuuuuuuuu/zmk-battery-bar
```
brew install --cask itouuuuuuuuu/tap/zmk-battery-bar
```
### Prospector dongle
https://github.com/carrefinho/prospector

## 3D print
https://www.printables.com/model/566288-improved-supports-kailh-choc-ergonomic-sculpted-ke
https://www.printables.com/model/400911-kailh-choc-ergonomic-sculpted-keycaps
https://www.printables.com/model/840146-totem-redux + remixes