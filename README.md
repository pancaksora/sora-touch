# Sora Touch

**Sora Touch** is a sleek, iOS-inspired touchscreen firmware for the LILYGO T-Pico3 board.  
Built with 💖 using LVGL, this firmware combines style, performance, and embedded wizardry.

## 🧩 Features
- iOS-style icon launcher with smooth UI
- 2.33" touchscreen support (GT911 + ST7789)
- WiFi auto-connect via ESP32-C6 co-processor
- BLE ready (for future BLE-Keyboard or remote)
- Built with PlatformIO

## 📦 Hardware Requirements
- LILYGO T-Pico3 (RP2040 + ESP32-C6)
- 2.33" IPS touchscreen (320x480)
- GT911 touch controller

## 🔧 Setup & Upload
git clone https://github.com/pancaksora/sora-touch.git
cd sora-touch
pio run -t upload
Make sure you're using the correct USB cable (data + power), and PlatformIO is installed.

🧠 Coming Soon
BLE keyboard mode
WiFi scanning tools
Custom themes
MQTT / dashboard support

Developed by @pancaksora
Powered by coffee ☕ and embedded chaos 🧠
