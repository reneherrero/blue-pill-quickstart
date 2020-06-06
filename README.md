# Rust Blue Pill Quickstart

![Rust](https://github.com/reneherrero/blue-pill-quickstart/workflows/Rust/badge.svg)

## Hardware

* [Blue Pill](https://stm32-base.org/boards/STM32F103C8T6-Blue-Pill.html) Minimum System Development board
* ST-Link V2 USB Programmer

## Dependencies for Debian Buster

* VS Code with the Rust and Cortex-Debug add-ins

* The thumbv7m-none-eabi Rust target
```bash
rustup target add thumbv7m-none-eabi
```

* OpenOCD
```bash
sudo apt-get install gdb-multi-arch
```

* GDB
```bash
sudo apt-get install gdb-multi-arch #or gdb-arm-none-eabi on some other Linux distros
```

## Run and Debug

Just put a breakpoint where you want it and press F5
