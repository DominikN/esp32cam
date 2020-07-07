# esp32cam: OV2640 camera on ESP32-CAM

[![GitHub build status](https://img.shields.io/github/workflow/status/yoursunny/esp32cam/build)](https://github.com/yoursunny/esp32cam/actions) [![GitHub code size](https://img.shields.io/github/languages/code-size/yoursunny/esp32cam?style=flat)](https://github.com/yoursunny/esp32cam)

**esp32cam** library provides an object oriented API to use OV2640 camera on ESP32 microcontroller.
It is a wrapper of [esp32-camera library](https://github.com/espressif/esp32-camera).
This library has been tested with AI Thinker [ESP32-CAM](http://wiki.ai-thinker.com/esp32-cam) board and OV2640 camera.

![esp32cam logo](docs/logo.svg)

## Installation

1. Clone this repository under `$HOME/Arduino/libraries` directory.
2. Clone `https://github.com/DominikN/WiFiWebServer` repository under `$HOME/Arduino/libraries` directory.
3. Clone `https://github.com/khoih-prog/WiFiNINA_Generic` repository under `$HOME/Arduino/libraries` directory.
3. Clone `https://github.com/khoih-prog/functional-vlpp` repository under `$HOME/Arduino/libraries` directory.
4. Add `#include <esp32cam.h>` to your sketch.
5. In *Tools* - *Board* menu, select **ESP32 Wrover Module** to take advantage of 4MB external PSRAM.
   Internal RAM is insufficient to support high resolution. **AI Thinker ESP32-CAM** is also fine, however it is not a good choice for handling hi res images.
6. Check out the [examples](examples/) for how to use.
