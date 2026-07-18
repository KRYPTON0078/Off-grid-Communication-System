# Off-Grid Communication System

Custom Meshtastic-oriented firmware and hardware integration for off-grid mesh communication on generic ESP32 + SX1278 LoRa hardware.

## Problem

Commercial mesh devices are not always available or affordable. Generic ESP32 + SX1278 boards need a reliable firmware port, pin mapping, and power/peripheral support to provide long-range off-grid messaging.

## Approach

- Ported/adapted Meshtastic firmware for generic ESP32 + SX1278 modules
- Implemented custom pin mapping for SPI, I2C, UART, GPS, battery monitoring, and OLED
- Added a custom board variant and PlatformIO build profile
- Modified radio initialization to detect and operate SX1278 modules across supported bands
- Assembled a portable device with battery system, OLED, optional GPS, and 3D-printed enclosure

## Tech stack

- C / C++
- ESP32
- SX1278 LoRa
- PlatformIO
- Meshtastic firmware base
- Optional GPS + OLED peripherals

## Results

- Working portable off-grid mesh node on generic hardware
- Support for LoRa, Bluetooth, GPS (optional), and low-power oriented configuration
- Reliable long-range communication demonstrated in portable assembled form

## My role

Firmware porting, board variant / pin mapping, PlatformIO configuration, radio bring-up, and physical device assembly (enclosure + power + peripherals).

## Relevance

Demonstrates **embedded systems** skill complementary to Edge AI: constrained hardware, radio bring-up, and real device integration.
