## 🚗 Toll Gate Monitoring System

A microcontroller-based embedded system designed to automate toll gate operations using LPC1768, ultrasonic sensors, and servo motors. This project was developed as part of the **Operating System & Embedded System Design** course.

## 📌 Problem Statement

Manual toll operations cause traffic congestion and delays. This system aims to provide an automated solution for detecting vehicles, controlling gate movement, and displaying real-time status to streamline toll operations.

## 🧠 Features

- Vehicle detection using ultrasonic sensor (HC-SR04)
- Automated gate control using servo motors
- Real-time LCD feedback (e.g., "Vehicle Detected", "Not in Range")
- Embedded C implementation on LPC1768 microcontroller

## 🧰 Components Used

- LPC1768 Microcontroller (ARM Cortex-M3)
- HC-SR04 Ultrasonic Sensor
- 16x2 LCD Display
- Servo Motors (x2)
- Power Supply (3.3V / 5V)

## 🔁 Working Principle

1. **Detection**: Ultrasonic sensor checks for vehicles in range.
2. **Processing**: LPC1768 processes distance data in real-time.
3. **Action**: If a vehicle is detected, the gate is opened using servo motors.
4. **Feedback**: LCD displays system status.
5. **Reset**: After the vehicle passes, the gate returns to standby mode.

## 💻 Code Overview

The main code handles:
- Sensor initialization and distance measurement
- Servo control logic for gate movement
- LCD control routines for displaying messages
- Main loop with continuous distance checking and decision-making

> The full code is available in [`code_main.docx`](./code_main.docx)

## 📸 Results

- Successfully detected approaching vehicles
- Actuated gate smoothly via servo motors
- Displayed accurate status on LCD
<img width="677" height="423" alt="results" src="https://github.com/user-attachments/assets/a32eb610-c2af-4237-b840-847464d87f39" />

## ✅ Conclusion

This project showcases a practical embedded system that reduces human intervention and traffic delays at toll gates. It demonstrates how microcontrollers and sensors can be integrated to create smart infrastructure solutions.

## 🚀 Future Enhancements

- RFID-based vehicle identification
- Remote monitoring via IoT integration
- Automated toll collection and payment system

## 📚 Team

- Akash Potdar (02FE22BEC003)
- Ayan Kudachi (02FE22BEC013)
- Pallavi Lad (02FE22BEC046)
- **Vaibhavi Patil** (02FE22BEC048)

Guided by:  
Dr. Swati Mavinkattimath  
Prof. Shweta Madiwalar

---

📅 Academic Year: **2024–25**  
🎓 Department of Electronics and Communication Engineering  
🏫 KLE Dr. M. S. Sheshgiri College of Engineering and Technology, Belagavi
