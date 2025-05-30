# 🌡️ Temp_Humidity_with_OLED

Бұл жоба Arduino Nano, DHT11 сенсоры және 
0.96" OLED дисплейін пайдаланып, температура мен ауа ылғалдылығын өлшеп. оларды OLED экранына шығарады.

## 🧰 Құрал-жабдықтар:
- Arduino Nano
- DHT11 температура және ылғалдылық сенсоры
- 0.96" OLED дисплей (I2C, 128x64)
- Сымдар және макет тақтасы

## 🔌 Жалғану сұлбасы:

| Компонент | Arduino Nano |
|-----------|--------------|
| OLED VCC  | 5V           |
| OLED GND  | GND          |
| OLED SDA  | A4           |
| OLED SCL  | A5           |
| DHT11 VCC | 5V           |
| DHT11 GND | GND          |
| DHT11 OUT | D3           |

## 📦 Қажетті кітапханалар:
- `Adafruit GFX`
- `Adafruit SSD1306`
- `DHT`

Кітапхана менеджері арқылы Arduino IDE ішінде орнатылады.

## Код

👉 [**Code_temp_hum.ino**](Code_temp_hum.ino) — жобаның негізгі бағдарламалық коды.

## ⏱ Жаңарту уақыты:
Экрандағы мәлімет 2 секунд сайын жаңарып тұрады.

## 🗣 Тіл:
Деректер ағылшын тілінде көрсетіледі.

---
