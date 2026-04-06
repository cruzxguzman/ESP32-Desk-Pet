# ESP32 Desk Pet

A Tamagotchi-style virtual pet built on an ESP32 with a 128x64 OLED display.

## Features
- Animated face with multiple moods (happy, hungry, tired, sad, dead)
- Food, happiness, and energy stats that drain in real time
- Feed, play, and sleep buttons
- Idle animations, blinking eyes, and pupil movement
- Death and revival system

## Hardware
- ESP32 WROOM-32
- SSD1309 128x64 OLED display (I2C)
- 3x tactile buttons

## Wiring
| Component | ESP32 Pin |
|---|---|
| OLED SDA | GPIO 21 |
| OLED SCL | GPIO 22 |
| Feed button | GPIO 32 |
| Happy button | GPIO 33 |
| Sleep button | GPIO 14 |

## Built With
- Arduino IDE
- U8g2 library
