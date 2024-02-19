# PolarFire SoM Board

Copyright (c) 2023-2024 [Antmicro](https://www.antmicro.com)

![](img/polarfire-som-photo.png)

## Overview

This project contains open hardware design files for the Antmicro PolarFire SoM Board, which is a System on Module containing PolarFire SoC MPFS250T processor, LPDDR4 SDRAM, eMMC Flash, along with WiFi and Bluetooth module.

The design files were prepared in KiCad 7.

This board exposes two 100-pin high density connectors, and is electrically compatible with [Raspberry Pi Compute Module 4](https://datasheets.raspberrypi.com/cm4/cm4-datasheet.pdf).

## Key features
* PolarFire SoC MPFS250T - the SoC FPGA with a RISC-V CPU cluster and a deterministic L2 memory subsystem
* 16 GB LPDDR4-1866 SDRAM
* 8 GB eMMC flash memory
* Gigabit Ethernet PHY
* 4-lane PCIe
* 2.4 GHz, 5.0 GHz IEEE 802.11 b/g/n/ac wireless
* Bluetooth 5.2
* HDMI output
* 4-lane MIPI DSI display port
* 4-lane MIPI CSI-2 camera port
* aditional 2-lane MIPI CSI-2 camera port, when working in 1.8V logic
* PMIC and Core supply buck converter providing 8 power rails from single 5V supply

## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains graphics for this README
* `doc` - contains schematics in PDF format
* `assets` - contains visual assets for showcasing this design on [Open Hardware Portal](https://openhardware.antmicro.com).


## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
