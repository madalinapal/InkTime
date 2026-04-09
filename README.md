# InkTime Watch

## Overview
InkTime Watch is a low-power smartwatch based on the nRF52840 microcontroller, designed for efficient timekeeping, motion tracking, and e-paper display usage.

## Hardware diagram & features
![Block diagram](images/block_diagram.jpg)

This is an open-hardware wearable based on the nRF52840 microcontroller. It is fully compatible with embedded C/C++ development and comes with the following features:

* [nRF52840](https://files.seeedstudio.com/wiki/XIAO-BLE/Nano_BLE_MCU-nRF52840_PS_v1.1.pdf) microcontroller (ARM Cortex-M4F @ 64 MHz, Bluetooth 5 / BLE, 2.4 GHz radio, 1 MB Flash and 256 KB RAM, multiple interfaces: SPI, I2C, UART, GPIO, support for external antenna)
* [E-paper Display](https://www.waveshare.com/1.54inch-e-paper-module.htm?srsltid=AfmBOooLaZDBFF5ey5FPMcwvfQjNszGLTJooliuUE0Pt89mi3RbbW3zz) 1.54 inch, 200x200 resolution, communicating via SPI interface
* [BMA423](https://watchy.sqfmi.com/assets/files/BST-BMA423-DS000-1509600-950150f51058597a6234dd3eaafbb1f0.pdf) accelerometer (3-axis ultra-low-power MEMS accelerometer, integrated step counting and activity recognition, motion detection interrupts, FIFO buffer, I2C/SPI interface, optimized for wearable low-power applications)
* [BQ25180](https://www.ti.com/product/BQ25180) LiPo Charger (I2C-controlled single-cell Li-Ion/Li-Po charger, 5V USB input, up to ~250 mA charging current, integrated power path management, ultra-low power for wearables)
* [250 mAh LiPo battery](https://elektronik.ropla.eu/pdf/stock/aky/aky1119.pdf)
* [FIT0774](https://www.tme.eu/ro/details/df-fit0774/motoare-dc/dfrobot/fit0774/) vibration motor (small DC vibration motor, 10 mm diameter, 2.7 mm height, 1.5–4.2 V operating voltage, used for haptic feedback in wearable devices)
* [TC2030-IDC](https://www.digikey.ro/ro/products/detail/tag-connect-llc/TC2030-IDC/4571121) debug connector (Tag-Connect 10-pin SWD programming interface, no-socket pogo-pin connector, supports SWDIO, SWDCLK, RESET, VCC and GND, used for low-profile in-circuit debugging of MCUs)
* [DRV2605L](https://www.ti.com/product/DRV2605L) haptic driver (I2C-controlled vibration motor driver with integrated haptic library, supports ERM and LRA actuators, automatic resonance tuning, low-power operation for wearable haptic feedback systems)
* [DS6160A](https://www.mouser.com/datasheet/2/1458/DS6160A_02-3104604.pdf?srsltid=AfmBOorjUBAXZpq5Z5uEI1jLcgjTr8TjWB5ry58Sj_L0fmmZSXPHWXP2) regulator (dual-channel low-power audio power amplifier / driver IC, designed for small speaker or actuator applications, wide supply voltage range, high efficiency Class-D operation, suitable for compact battery-powered systems)
* [MAX17048](https://www.analog.com/en/products/max17048.html) fuel gauge (ultra-low-power single-cell Li-ion battery fuel gauge IC, I2C interface, uses ModelGauge algorithm for accurate state-of-charge estimation, no external sense resistor required, optimized for wearable and portable devices)

![Smartwatch exploded view](images/smartwatch_exploded_view.png)
