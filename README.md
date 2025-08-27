# ESPHome Predator 3500 Generator Controller

This project provides an ESPHome-based controller for automating the start-up and monitoring of a Predator 3500 generator. The controller is designed to actuate the choke, activate the starter for a configurable duration, and monitor generator output using a light sensor placed on the output indicator light.

## Features

- **Choke Actuation:** Automatically controls the generator's choke during start-up.
- **Starter Activation:** Engages the starter for a settable time period to ensure reliable engine start.
- **Output Monitoring:** Uses a light sensor to detect the generator's output status via the output indicator light.
- **Configurable Parameters:** Starter activation time and other settings can be adjusted via ESPHome configuration.
- **Remote Control & Monitoring:** Integrates with Home Assistant for remote operation and status updates.

## Hardware Requirements

- ESP8266 or ESP32 microcontroller
- Predator 3500 generator
- Relay or actuator for choke control
- Relay for starter activation
- Light sensor (e.g., LDR or photodiode) positioned on the generator's output light
- Power supply for ESP device

## Setup

1. Connect the choke and starter actuators to the ESP device via relays.
2. Mount the light sensor on the generator's output indicator light.
3. Flash the ESP device with the provided ESPHome configuration.
4. Integrate with Home Assistant for remote control and monitoring.

## Configuration

All operational parameters (such as starter activation time) can be set in the ESPHome YAML file. Adjust these values to match your generator's requirements.

## Safety Notice

Ensure all wiring and modifications are performed safely and in accordance with the generator's manual. Improper installation may result in equipment damage or personal injury.

## License

This project is open source under the MIT License.