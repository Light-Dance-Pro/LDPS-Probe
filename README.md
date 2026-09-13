# LDPS Probe

ESP32-S3 production-test-board firmware combining an ESP-NOW bridge, SX1262 transmitter, WS2812
RMT signal analyzer, I2C sniffer, and 12 V ADC measurement.

## Repository navigation

- [STATUS.md](STATUS.md) — current capability and physical-verification boundary.
- [docs/index.md](docs/index.md) — component documentation map and platform authority links.

## Build

The PlatformIO `probe` environment builds and uploads the firmware. Always select the exact serial
port when uploading to avoid writing to another connected ESP32 device.
