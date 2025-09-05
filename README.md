
# ESP8266 LED Control Web Server 🌐💡

This project demonstrates how to control an LED using an ESP8266  via a Web Server with HTML + CSS.

## 🚀 Features
- Turn LED ON/OFF from browser
- Clean HTML + CSS interface
- WiFi connection with ESP8266
- Works on any device connected to same WiFi

## 🔌 Circuit Diagram
- ESP8266 GPIO2 (D4) → LED (via 220Ω resistor) → GND

![circuit](https://github.com/AmeySecOps/ESP8266-LED-WebServer./blob/40dd77d61ce31837497cc5c9f97dbfbbfa0a8b33/source%20code/circuit%20.jpg)

## 📷 Demo
#Led on 
![screenshot](https://github.com/AmeySecOps/ESP8266-LED-WebServer./blob/0617f045e6ccc23fc489cde5a2fc35fe7303d06d/source%20code/ledon.png)

#Led off 
![Screenshot](https://github.com/AmeySecOps/ESP8266-LED-WebServer./blob/8c3aeb9996efafcd8ee6e47ea6f8575b6a1b117f/source%20code/ledoff.png)

#video
![video](https://github.com/AmeySecOps/ESP8266-LED-WebServer./blob/0cf1c4c9497ae65b792d0f25bbabc9b3c3d9d914/source%20code/working%20project%20.mp4)

## 📂 Project Structure

## 🛠️ Requirements
- Arduino IDE
- ESP8266 Board Package
- ESP8266WiFi & ESP8266WebServer libraries

## ▶️ How to Run
1. Install ESP8266 board in Arduino IDE
2. Update your WiFi SSID & password in code
3. Upload code to ESP8266
4. Open Serial Monitor → Copy IP address
5. Open IP in browser → Control LED!

## ✨ Future Improvements
- Show LED status on webpage
- Control multiple devices
- Add authentication
- IoT cloud integration (MQTT, Blynk)

---
Made with ❤️ by Amey
