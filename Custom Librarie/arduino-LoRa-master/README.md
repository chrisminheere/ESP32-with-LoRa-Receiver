# Arduino LoRa

[![Build Status](https://travis-ci.org/sandeepmistry/arduino-LoRa.svg?branch=master)](https://travis-ci.org/sandeepmistry/arduino-LoRa)

An [Arduino](https://arduino.cc/) library for sending and receiving data using [LoRa](https://www.lora-alliance.org/) radios.

## Compatible Hardware



### Semtech SX1276/77/78/79 wiring

| Semtech SX1276/77/78/79 | Arduino |
| :---------------------: | :------:|
| VCC | 3.3V |
| GND | GND |
| SCK | SCK |
| MISO | MISO |
| MOSI | MOSI |
| NSS | 17 |
| NRESET | 14 |
| DIO0 | 2 |


**NOTES**:
 * Some boards (like the Arduino Nano), cannot supply enough current for the SX127x in TX mode. This will cause lockups when sending, be sure to use an external 3.3V supply that can provide at least 120mA's when using these boards.
 * If your Arduino board operates at 5V, like the Arduino Uno, Leonardo or Mega, you will need to use a level converter for the wiring to the Semtech SX127x module. Most Semtech SX127x breakout boards do not have logic level converters built-in.

## Installation

### Using the Arduino IDE Library Manager

1. Choose `Sketch` -> `Include Library` -> `Manage Libraries...`
2. Type `LoRa` into the search box.
3. Click the row to select the library.
4. Click the `Install` button to install the library.

## API

See [API.md](API.md).


