# Awesome Waveshare ESP32-S3-Touch-AMOLED-2.06

> A curated list of firmware, hardware resources and projects for Waveshare ESP32-S3-Touch-AMOLED-2.06.

[![ESP32](https://img.shields.io/badge/chip-ESP32_S3-red)](https://www.espressif.com/en/products/socs)
[![Framework](https://img.shields.io/badge/framework-ESP--IDF%20%7C%20Arduino-blue)](#firmware--sdks)
[![License: CC0](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)](CONTRIBUTING.md)

The ESP32-S3-Touch-AMOLED-2.06 is a high-performance, wearable watch-style development board designed by Waveshare. Based on the ESP32-S3R8 microcontroller, it integrates a 2.06inch capacitive touch AMOLED display, a 6-axis IMU, an RTC, an audio codec, power management, and a TF card slot. It comes with a custom case and a detachable strap, making it ideal for wearable device prototyping, functional verification, and interactive application development.

Official links: [Website](https://www.waveshare.com/) · [Store](https://www.waveshare.com/esp32-s3-touch-amoled-2.06.htm) · [Docs](https://docs.waveshare.com/ESP32-S3-Touch-AMOLED-2.06)

---

## Contents

- [Device Overview](#device-overview)
- [Official resources](#official-resources)
- [Projects & Examples](#projects--examples)
- [Videos](#videos)

---

## Device Overview

| Spec | Details |
|------|---------|
| **MCU** | ESP32 S3 |
| **Flash / PSRAM** | 32 MB / 8 MB |
| **Display** | CO5300 2.06" AMOLED 410x502 |
| **Touch** | FT3168 |
| **IMU** | QMI8658C, 6-axis (Accelerometer + Gyroscope) |
| **RTC** | PCF85063ATL |
| **Audio Codec** | ES8311 (speaker with pa) |
| **Microphone** | ES7210 (2 mics) |
| **Memory** | Micro SD slot |
| **Power** | AXP2101 |

## Official resources

### Official Firmware

- [Firmware](https://docs.waveshare.com/ESP32-S3-Touch-AMOLED-2.06/Instructions-For-Use) - Factory firmware.

### Board Support Packages

- [waveshare/esp32_s3_touch_amoled_2_06](https://components.espressif.com/components/waveshare/esp32_s3_touch_amoled_2_06/versions/2.0.0/readme) - ESP-IDF board support package.

## Projects & Examples

### Official Examples

- [ESP32-S3-Touch-AMOLED-2.06](https://github.com/waveshareteam/ESP32-S3-Touch-AMOLED-2.06) - Official Arduino / ESP-IDF examples.

### Community Projects

- [waveshare-watch-rs](https://github.com/infinition/waveshare-watch-rs) - 100% Rust `no_std` smartwatch firmware for the Waveshare ESP32-S3-Touch-AMOLED-2.06
- [Picoware](https://github.com/jblanked/Picoware) - Open-source custom firmware for PicoCalc, Cardputer ADV, Flipper Zero, POOM, and other ESP32/Raspberry Pi Pico devices
- [Launcher](https://github.com/bmorcelli/Launcher) - Firmware Launcher for ESP32 boards like: M5Stack, Lilygo, Marauder and CYD devices.
- [chronos-amoled](https://github.com/nevelate/chronos-amoled) - Chronos Watchy ported to Waveshare ESP32-S3-Touch-AMOLED-2.06 [WIP]
- [Chronos-navio](https://github.com/fbiego/chronos-navio) - Chronos Navigation firmware for ESP32-based devices
- [cubeboy](https://github.com/nevelate/cube-boy/tree/amoled) - Play Gameboy & GBC games on an ESP32-S3! [WIP] 

## Videos

- [Battery Installation Tutorial】Waveshare ESP32-S3-Touch-AMOLED-2.06](https://www.youtube.com/watch?v=5HYsyMwuWq0) - Waveshare Electronics
- [ESP32 + Smartwatch = Smart Home Control!](https://www.youtube.com/watch?v=pLcABak9Scc) - Volos Projects
