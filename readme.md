# WLED Controller
The smallest and the cheapest ESP-01 based controller for WS2812B LED strip. Controller size is 24.8x14.5 mm. Designed specifically for WLED firmware.

<img src="images/controller.png">


## Table of Contents
- [WLED Firmware](#wled-firmware)
- [Ambilight with Hyperion](#ambilight-with-hyperion)
  * [Ambilight videos](#ambilight-videos)
- [How to DIY](#how-to-diy)
  * [Schematic](#schematic)
  * [Printed circuit board](#printed-circuit-board)
  * [3D Model](#3d-model)
- [How to buy](#how-to-buy)


## WLED Firmware
<a href="https://github.com/Aircoookie/WLED">WLED by Aircoookie</a> is a fast and feature-rich implementation of an ESP8266/ESP32 webserver to control NeoPixel (WS2812B, WS2811, SK6812) LEDs!

Installed 4MB flash memory provides full WLED firmware support, including Over-The-Air updates.

<img src="images/wled-render.png">


## Ambilight with Hyperion
<a href="https://github.com/hyperion-project/hyperion.ng">Hyperion</a> is an open source implementation of Ambient Lighting that supports many LED devices and video capturers. 

WLED devices are discovered automatically by Hyperion.

### Ambilight videos
https://user-images.githubusercontent.com/49450780/193467004-ad8659e0-2ca4-4e45-a21f-c46aeb7bf4c0.mp4

https://user-images.githubusercontent.com/49450780/193467104-2082a0d3-7ae6-40a5-b760-2eaae8f833c8.mp4


## How to DIY
You can assemble WLED Controller yourself using the information below.

### Schematic
<img width="600px" src="images/schema.png">

- **MK1**: ESP-01/ESP-01s
- **U1**: AMS1117 3.3v, SOT-89
- **R1, R2, R3**: 10k, 0805
- **C1**: 10u, 0805
- **C2**: 22u, 0805
- **USB1**: Micro USB 5S-B

### Printed circuit board
The PCB (Gerber) files are in this repository.

<img width="600px" src="images/2D-pcb.png">

### 3D Model
<img width="400px" src="images/3D-model.png">


## How to buy
You will be able to order WLED Controller after **1 Nov 2022**. The purchase link will be on this page.
