# 🌡️ Temp_Humidity_with_OLED

This project uses Arduino Nano, a DHT11 sensor, and a 
0.96" OLED display to measure temperature and humidity.

## 🧰 Components:
- Arduino Nano
- DHT11 temperature and humidity sensor
- 0.96" OLED display (I2C, 128x64)
- Jumper wires and breadboard

## 🔌 Wiring:

| Component | Arduino Nano |
|-----------|--------------|
| OLED VCC  | 5V           |
| OLED GND  | GND          |
| OLED SDA  | A4           |
| OLED SCL  | A5           |
| DHT11 VCC | 5V           |
| DHT11 GND | GND          |
| DHT11 OUT | D3           |

## 📦 Required Libraries:
- `Adafruit GFX`
- `Adafruit SSD1306`
- `DHT`

Install them via the Arduino Library Manager.

## ⏱ Refresh Rate:
Data updates every 2 seconds.

## 🗣 Language:
Displayed in **English language**.

---
