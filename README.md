# Ultrasonic Sensor Radar 
# 🛰️ Arduino Radar System using Ultrasonic Sensor & Servo Motor

A DIY radar simulation project using **Arduino UNO**, **HC-SR04 Ultrasonic Sensor**, and **SG90 Servo Motor**. This project scans the environment and visualizes nearby objects on a radar-style display using **Processing IDE**.

> #🔧 Developed by **Sai Vikram Balaji B** 
---

## 📡 What is Arduino Radar?

An **Arduino Radar System** mimics real radar functionality using ultrasonic waves. A servo-mounted sensor rotates and scans its surroundings. Detected objects are visualized on a simulated radar interface created in Processing.

---

## ⚙️ How It Works

1. The servo rotates the ultrasonic sensor in an arc.
2. The sensor sends ultrasonic pulses and listens for reflections.
3. Arduino calculates distances and angles.
4. Data is transmitted via serial to a computer.
5. Processing IDE displays a radar-like graphical interface.

---

## 🔩 Components Required

| Component               | Quantity | Description                          |
|------------------------|----------|--------------------------------------|
| Arduino UNO            | 1        | Main controller                      |
| HC-SR04 Ultrasonic Sensor | 1     | For distance measurement             |
| SG90 Servo Motor       | 1        | Rotates the ultrasonic sensor        |
| Breadboard             | 1        | Circuit connections                  |
| Jumper Wires           | As needed| Wiring                               |
| USB Cable (Type B)     | 1        | Connect Arduino to PC                |
| Processing IDE         | 1        | For graphical radar display          |

---

## 🔌 Circuit Diagram


 ![image alt](https://github.com/SaiVikramBalaji2004/ultrasonic_sensor_radar/blob/22172ccb378fa453258380fbf5fa401bb75d6ef8/project.jpg)

---

## 💻 Software Setup

### 1. Arduino Sketch

Upload the `Arduino_Radar.ino` to your UNO using the Arduino IDE. It handles servo movement, ultrasonic sensing, and serial communication.

### 2. Processing Radar Interface

Open `Radar_Interface.pde` in [Processing IDE](https://processing.org/download) and run it. The radar visualization will begin based on the Arduino's serial output.

---

## 📁 Project Structure

arduino-radar/
 - Arduino_Radar.ino # Arduino sketch
 - Radar_Interface.pde # Processing sketch for radar GUI
 - wiring_diagram.png # Circuit diagram image
 - ADME.md # This file

---

## 🚀 How to Use

1. Build the circuit as per the diagram.
2. Upload the Arduino code.
3. Open and run the Processing sketch.
4. Watch the radar sweep and detect nearby objects in real time!

---

## 🛠️ Improvements Ideas

- Add buzzer alerts for close objects
- Use OLED for real-time distance display
- Integrate Bluetooth/Wi-Fi to send data remotely
- Extend sweep range and angle dynamically

---

## 🧠 Learning Outcomes

- Real-time sensor interfacing
- Serial communication between Arduino & PC
- Graphical visualization using Processing
- Basics of radar and object detection systems

---


> 📡 "Scan your surroundings, one servo sweep at a time!"  
