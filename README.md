🌡️ Temperature-Controlled Fan System using DHT22 & Arduino

This project implements an automated temperature monitoring and cooling system using an Arduino, a DHT22 temperature & humidity sensor, an I2C LCD display, and a relay module to control a fan.

🔧 Features
Reads real-time temperature and humidity using the DHT22 sensor
Displays temperature readings on a 16x2 I2C LCD
Automatically turns a fan ON/OFF based on a predefined temperature threshold
Provides serial output for debugging and monitoring
Handles sensor read errors gracefully

⚙️ How It Works
The system continuously reads temperature data from the DHT22 sensor
If the temperature exceeds 30°C, the relay is activated (Active LOW), turning the fan ON
If the temperature drops below the threshold, the fan is turned OFF
The LCD displays:
Current temperature
Fan status (ON / OFF)

🧩 Hardware Components
Arduino board (Uno, Nano, etc.)
DHT22 temperature & humidity sensor
16x2 LCD with I2C module
Relay module (Active LOW)
Fan (or any load)

🔌 Pin Configuration
DHT22 Data Pin → Digital Pin 5
Relay Control Pin → Digital Pin 3
LCD → I2C (Address: 0x27)
