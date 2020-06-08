# Rust Blue Pill Quickstart

![Rust](https://github.com/reneherrero/blue-pill-quickstart/workflows/Rust/badge.svg)

## Hardware

* [Blue Pill](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill.html) Minimum System Development board
![blue pill pinout](BluePillPinout.jpg "blue pill pinout")

* ST-Link V2 USB Programmer
![ST-Link V2](STLinkV2.jpg "ST-Link V2")

## Dependencies for Debian Buster

* VS Code with the Rust and Cortex-Debug add-ins
If you have the `code` command in your path, you can run the following commands to install the necessary extensions.

```sh
code --install-extension rust-lang.rust
code --install-extension marus25.cortex-debug
```

* The thumbv7m-none-eabi Rust target
```bash
rustup target add thumbv7m-none-eabi
```

* OpenOCD
```bash
sudo apt-get install openocd
```

* GDB
```bash
sudo apt-get install gdb-multi-arch #or gdb-arm-none-eabi on some other Linux distros
```

## Run and Debug

Just put a breakpoint where you want it and press F5
