# 🚗 Arduino Projects Collection

This repository contains a collection of simple yet educational Arduino-based projects for beginners and intermediate learners. Each sketch demonstrates basic usage of various Arduino-compatible components such as ultrasonic sensors, LCD displays, IR sensors, and servo motors.

---

## 📁 Included Projects

### 1. 🔊 Ultrasonic Distance Alert System (`ultrasonic_alert.ino`)

**Description**:  
This sketch uses an HC-SR04 ultrasonic sensor to measure the distance of nearby objects. If an object is detected within 5 cm, a buzzer and LED are activated as an alert.

**Components**:
- HC-SR04 Ultrasonic Sensor  
- Buzzer  
- LED  
- Arduino UNO  

**Key Features**:
- Real-time distance measurement  
- Visual (LED) and audible (buzzer) alerts  
- Serial Monitor output  

---

### 2. 💬 LCD Display Control Demo (`lcd_display_toggle.ino`)

**Description**:  
Demonstrates how to control a 16x2 LCD using the `LiquidCrystal` library. The sketch prints "hello, world!" and toggles the LCD display ON and OFF every 500 ms.

**Components**:
- 16x2 LCD (HD44780 compatible)  
- 10k potentiometer for contrast  
- Arduino UNO  

**Key Features**:
- LCD display initialization and text output  
- Usage of `display()` and `noDisplay()` functions  

---

### 3. 🅿️ Smart Parking Gate with IR Sensors and Servo (`ir_parking_gate.ino`)

**Description**:  
A smart parking gate system using two IR sensors to detect vehicle movement and a servo motor to control the gate. The system opens the gate when a car is detected and simulates parking space logic.

**Components**:
- 2 IR Sensors  
- Servo Motor  
- Arduino UNO  

**Key Features**:
- Vehicle detection using IR  
- Automated gate control using servo  
- Basic parking logic simulation  

---

## 🧪 How to Use

1. Clone or download this repository.
2. Open any `.ino` file using the Arduino IDE.
3. Connect the required components as per the inline comments.
4. Upload to your Arduino board and observe the behavior.

---

## 📦 Folder Structure

arduino-projects/
│
├── ultrasonic_alert.ino # Ultrasonic Distance Alert System
├── lcd_display_toggle.ino # LCD display toggle demo
└── ir_parking_gate.ino # Smart IR-based parking system
