# automatic-street-light-arduino
automatic street light using arduino and ldr - wokwi simulation

## Project Overview

This project is an automatic street light system developed using Arduino Uno and an LDR (Light Dependent Resistor).

The system detects the surrounding light intensity and automatically controls an LED.

## Objective

To automatically turn the street light ON when the surroundings become dark and turn it OFF when sufficient light is available.

## Components

- Arduino Uno
- LDR / Photoresistor
- LED
- 220 Ω Resistor

## Software

- Wokwi Simulator
- Arduino C/C++

## Working Principle

The LDR detects the surrounding light intensity and sends an analog signal to the Arduino through analog pin A0.

The Arduino reads the sensor value and compares it with a predefined threshold.

If the detected light level indicates darkness, the Arduino turns the LED ON.

If sufficient light is detected, the Arduino turns the LED OFF.

## Pin Connections

| Component | Arduino Pin |
|---|---|
| LDR VCC | 5V |
| LDR GND | GND |
| LDR AO | A0 |
| LED | D8 |

## Simulation

The project was designed and tested using the Wokwi online simulator.

## Future Enhancement

The system can be extended to control multiple street lights and can later be implemented using an ESP32 for IoT-based monitoring.
