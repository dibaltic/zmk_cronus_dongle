This is the firmware for [cronus keyboard](https://github.com/dibaltic/cronus) if you would like to use the keyboard with a dongle. You will need an additional MCU to use as your dongle, it doesn't need to be the same as what you are using on your keyboard, but should be one supported by [ZMK boards](https://zmk.dev/docs/hardware). For more information on dongles and their usage in ZMK please refer to the [docs](https://zmk.dev/docs/development/hardware-integration/dongle)

## Getting Started
If you'd like to make your own firmware.
[Here are the instructions to get started.](https://github.com/dibaltic/zmk_cronus_dongle/blob/main/getting_started.md)

Alternatively, to use my keymap as it is you can download the firmware from the [latest action run](https://github.com/dibaltic/zmk_cronus_dongle/actions), and then refer to the [ZMK docs](https://zmk.dev/docs/user-setup#installing-the-firmware) to flash the firmware to your keyboard and dongle.

> Note: If you opt to use a different MCU for your dongle you will need to change the [build.yaml](https://github.com/dibaltic/zmk_cronus_dongle/blob/main/build.yaml) dongle board to the board you are intending to use. I have the firmware setup for a nice!nano v2 compatible controller as the dongle.

## Keymap Reference
It is based on the [bird layout](https://github.com/jcmkk3/bird-layout)


![ZMK Cronus](https://github.com/user-attachments/assets/41fb7a06-e676-4a0b-bb9e-e6c683aa6120)
