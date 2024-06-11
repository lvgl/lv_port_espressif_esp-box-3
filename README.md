# LVGL ported to ESP32-S3-BOX-3

## Overview

This is LVGL ported to [ESP32-S3-BOX-3](https://github.com/espressif/esp-bsp/tree/master/bsp/esp-box-3) with using Espressif [BSP](https://github.com/espressif/esp-bsp). This example shows LVGL music demo.

| <div align=center><img src="https://github.com/espressif/esp-bsp/blob/master/docu/pics/esp32_s3_box_3.png?raw=true" width=400/></div> | <div align=center><img src="https://github.com/espressif/esp-bsp/blob/master/bsp/esp-box-3/pic.png?raw=true" width=800/></div> |
| :----: | :----: |

## Buy

You can purchase ESP32-S3-BOX-3 from [MOUSER](https://mou.sr/3VlYRo6).

## Benchmark

You can find more about performance in [BSP repository](https://github.com/espressif/esp-bsp/blob/master/components/esp_lvgl_port/docs/performance.md).

## Specification

### CPU and Memory
- **MCU:** ESP32-S3
- **RAM:** 512 KB internal SRAM,  8/16 MB external PSRAM
- **Flash:** 2/4/8/16 MB

### Display and Touch
- **Resolution:** 320x240
- **Display Size:** 2.4"
- **Interface:** SPI (ILI9341)
- **Color Depth:** 24-bit
- **Touch Pad:** Capacitive (GT911)

### Connectivity
- Onboard audio codec + audio amplifier
- Onboard dual microphone pickup
- Onboard IMU
- USB type-C interface download and debugging

## Getting started

### Hardware setup
- Connect USB-C (next to the screen) to PC
- [Board User Guide](https://github.com/espressif/esp-box/blob/master/docs/getting_started.md)

### Software setup
- Prepare environment for compiling ESP-IDF - follow this [guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html).

### Run the project
- Clone this repository
- Compile and flash
```
idf.py -p COMx flash monitor
```

## Contribution and Support

If you find any issues with the development board feel free to open an Issue in this repository. For LVGL related issues (features, bugs, etc) please use the main [lvgl repository](https://github.com/lvgl/lvgl).

If you found a bug and found a solution too please send a Pull request. If you are new to Pull requests refer to [Our Guide](https://docs.lvgl.io/master/CONTRIBUTING.html#pull-request) to learn the basics.

