# Smart Health Monitor using STM32F103C8T6

This project is a Smart Health Monitoring System built with the STM32F103C8T6 (Blue Pill) microcontroller. It uses a MAX30100 sensor to measure heart rate and SpO2, a DS18B20 sensor for temperature, and a 16x2 LCD to display readings.

## 📦 Components Used
- STM32F103C8T6 (Blue Pill)
- MAX30100 Pulse Oximeter Sensor
- DS18B20 Temperature Sensor
- 16x2 LCD
- ST-Link V2 Programmer
- Touch Sensor Module
- Jumper wires, Breadboard, etc.

## 🔧 Tools and Libraries
- Arduino IDE with STM32 board support (STM32duino core)
- Libraries: `MAX30100_PulseOximeter`, `LiquidCrystal`, `OneWire`, `DallasTemperature`
- STM32CubeProgrammer for uploading via ST-Link

## 📋 Features
- Displays Heart Rate and SpO2 when finger is detected via touch sensor
- Displays temperature when DS18B20 reads a valid body temp
- LCD goes idle after 5 seconds of inactivity

## 🔌 Pin Configuration

| Component     | Pin on STM32 |
|---------------|--------------|
| LCD RS        | PA0          |
| LCD E         | PA1          |
| LCD D4–D7     | PA2–PA5      |
| MAX30100 SDA  | PB7          |
| MAX30100 SCL  | PB6          |
| DS18B20 Data  | PB0          |
| Touch Sensor  | PB8          |

## 📷 Circuit Diagram
![Circuit Diagram](images/circuit_diagram.png)

## 📁 File Structure
- `code/` – Arduino source code (`.ino`)
- `docs/` – Final report and parts list
- `images/` – Schematic or photos

## 📝 License
This project is open-source. Feel free to modify or build on it!

