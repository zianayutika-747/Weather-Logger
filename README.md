# Weather Logger Using Arduino and DHT22

## Project Overview

This project is a simple weather monitoring system that measures temperature and humidity using a DHT22 sensor interfaced with an Arduino Uno. The sensor readings are displayed in real time through the Serial Monitor, making it useful for environmental monitoring and data logging applications.

## Objective

To develop a weather logging system that continuously monitors and displays temperature and humidity values.

## Components Required

* Arduino Uno
* DHT22 Temperature and Humidity Sensor
* Breadboard
* Jumper Wires
* 10kΩ Resistor (for physical hardware setup)
* USB Cable

## Software Used

* Arduino IDE
* Wokwi Simulator

## Circuit Connections

| DHT22 Pin  | Arduino Uno Pin |
| ---------- | --------------- |
| VCC        | 5V              |
| SDA (DATA) | D2              |
| NC         | Not Connected   |
| GND        | GND             |


## Working Principle

The DHT22 sensor measures environmental temperature and humidity. The Arduino reads these values periodically and sends the data to the Serial Monitor. The readings are updated every two seconds, allowing continuous monitoring of environmental conditions.

## Sample Output

Temperature: 28.5 °C  Humidity: 62.3 %

Temperature: 28.7 °C  Humidity: 62.1 %

Temperature: 28.9 °C  Humidity: 61.9 %

## Applications

* Weather Monitoring Systems
* Smart Agriculture
* Greenhouse Monitoring
* Environmental Research
* Climate Analysis
* IoT-Based Monitoring Systems

## Learning Outcomes

* Understanding sensor interfacing with Arduino.
* Acquiring real-time environmental data.
* Monitoring and logging temperature and humidity.
* Developing basic embedded system applications.

## Future Enhancements

* Store readings in an SD card.
* Display data on an LCD/OLED screen.
* Upload sensor data to cloud platforms.
* Send alerts when temperature exceeds a threshold.

## Conclusion

The Weather Logger project successfully measures and displays temperature and humidity using a DHT22 sensor and Arduino Uno. The system provides a simple and effective solution for real-time environmental monitoring.
