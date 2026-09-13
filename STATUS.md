# Status — LDPS Probe

The firmware implements ESP-NOW bridging, SX1262 v2 frame transmission, sequential eight-channel
WS2812 RMT capture, passive I2C observation, and 12 V ADC measurement.

Recorded bench evidence covers all eight WS2812 channels and I2C detection. The SX1262 path has
been updated to the 14-byte v2 protocol and builds successfully, but the updated path has not been
re-verified on the physical jig and Node. Until that check is recorded, build success is not proof
of RF interoperability.

The source identifies FPS calculation, expected-pattern comparison, and dropped-frame detection as
unimplemented capabilities.
