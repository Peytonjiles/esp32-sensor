# ESP32 Sensor Project

## Overview
This project demonstrates how to use an **ESP32** with a basic sensor (the kind often included in Raspberry Pi kits) and a **speaker/piezo buzzer**.  
The ESP32 reads data from the sensor and can also play simple melodies through the speaker.  

It includes:
- `sensor_distance.ino` → Arduino sketch for reading the sensor
- `pitches.h` & `toneMelody.txt` → Tone and melody definitions
- `layout.png` & `schematic.png` → Wiring and circuit diagrams

---

## Disclaimer ⚠️
I am **not responsible** if this project breaks your hardware, stops working, or behaves differently than expected.  
Use it **at your own risk**.  

---

## Hardware Requirements
You will need:
- An **ESP32 development board**  
- A **regular sensor** (like the ones found in Raspberry Pi starter kits)  
- A **speaker / piezo buzzer**  
- Jumper wires & breadboard  

---

## Software Requirements
- [Arduino IDE](https://www.arduino.cc/en/software)  
- ESP32 board support (installed through Arduino Boards Manager)  

---

## Setup
1. Download or clone this repository.  
2. Open `sensor_distance.ino` in Arduino IDE.  
3. Copy `pitches.h` into the same folder as the sketch.  
4. Connect your **sensor** and **speaker** following the provided `schematic.png` or `layout.png`.  
5. Upload the sketch to your ESP32.  
6. Open the Serial Monitor to see the sensor readings and hear melodies from the speaker.  

---

## File Structure
