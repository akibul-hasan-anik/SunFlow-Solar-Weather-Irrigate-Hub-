# SunFlow: Solar Weather Irrigate Hub
SunFlow is a smart agriculture system that combines automatic irrigation, weather monitoring, and solar energy optimization using Arduino. The system monitors environmental conditions such as soil moisture, temperature, humidity, rainfall, and sunlight to automate irrigation and improve energy efficiency. The project aims to support sustainable farming by conserving water, reducing manual labor, and using renewable solar energy to power the system.

# Features
* Automatic irrigation based on soil moisture level
* Weather monitoring using temperature, humidity, and rain sensors
* Solar panel tracking for maximum sunlight exposure
* LCD display for real-time system status
* Relay-controlled water pump
* Improves water efficiency and crop health

# Hardware Components
* Arduino Uno R3
* Soil Moisture Sensor
* DHT11 Temperature & Humidity Sensor
* Rain Sensor
* LDR Sensors
* Servo Motor
* Solar Panel
* Relay Module
* Water Pump
* LCD Display (I2C)
* Breadboard & Jumper Wires
* 3.7V LiPo Battery

# Arduino Files
# sketch_1.ino
This file implements the smart irrigation and weather monitoring system.
Functions:
* Reads soil moisture sensor to determine irrigation needs
* Monitors temperature and humidity using DHT11
* Detects rain conditions
* Displays system status on LCD
* Controls the water pump through a relay module

# sketch_2.ino
This file implements the solar panel tracking system.
Functions:
* Uses two LDR sensors to detect sunlight intensity
* Compares light levels between sensors
* Rotates a servo motor to align the solar panel toward maximum sunlight
* Improves solar energy collection efficiency
