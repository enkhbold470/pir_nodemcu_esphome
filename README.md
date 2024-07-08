# Custom PIR Sensor Module with ESP8266 Firmware

This repository contains the firmware code and documentation for building a custom PIR (Passive Infrared) sensor module using ESP8266 firmware of ESPhome for integration with Home Assistant.

## Table of Contents

- [Introduction](#introduction)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The custom PIR sensor module allows you to detect motion using passive infrared technology. By integrating it with Home Assistant, you can automate various tasks based on motion detection, such as turning on lights, triggering alarms, or adjusting temperature settings.

## Hardware Requirements

To build the custom PIR sensor module, you will need the following components:

- ESP8266 development board
- PIR sensor
- Jumper wires
- Breadboard or PCB for prototyping

## Software Requirements

The firmware for the custom PIR sensor module is developed using ESPhome, an open-source framework for ESP8266 and ESP32 microcontrollers. You will also need the Arduino IDE or PlatformIO for uploading the firmware to the ESP8266 board.

## Installation

1. Clone or download this repository to your local machine.
2. Connect the ESP8266 development board to your computer using a USB cable.
3. Open the firmware code in the Arduino IDE or PlatformIO.
4. Configure the necessary settings in the code, such as Wi-Fi credentials and Home Assistant integration.
5. Upload the firmware to the ESP8266 board.

## Configuration

Before uploading the firmware, make sure to configure the following settings in the code:

- Wi-Fi credentials: Provide the SSID and password of your Wi-Fi network.
- Home Assistant integration: Set up the MQTT broker and topic for communication with Home Assistant.
- ESPhome config [tutorials](https://esphome.io)

## Usage

Once the firmware is uploaded and the custom PIR sensor module is connected to your Home Assistant instance, you can start using it to automate tasks based on motion detection. Refer to the Home Assistant documentation for more information on configuring automations and triggers.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
