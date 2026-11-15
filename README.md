# Sound Detection Using Arduino Uno

## Project Description
This project detects sound using a sound sensor and controls an LED based on the sensor reading.

When the sound reading is greater than 550, the LED turns ON. Otherwise, the LED remains OFF.

## Components Required
- Arduino Uno
- KY-038 Sound Sensor
- Red LED
- 220Ω Resistor
- Jumper Wires

## Circuit Connections

| Component | Arduino Pin |
|---|---|
| Sensor VCC | 5V |
| Sensor GND | GND |
| Sensor AO | A0 |
| LED Positive | D8 through 220Ω resistor |
| LED Negative | GND |

## Working Principle
1. The sound sensor reads sound levels.
2. Arduino reads the sensor value through analog pin A0.
3. Arduino compares the reading with the threshold value 550.
4. If the reading is greater than 550, the LED turns ON.
5. Otherwise, the LED turns OFF.

## Sensor Reading Interval
100 milliseconds.

## Software Used
- Wokwi Simulator
- Arduino Uno
- Arduino C++

## Wokwi Simulation
https://wokwi.com/projects/480758788249713665

## Expected Output
- Sound value greater than 550: LED ON.
- Sound value 550 or below: LED OFF.