#  Plaza Robotic Car Project

##  Overview

This project is a **robotic car with a robotic arm** designed for the Plaza competition.
The car can operate in both **manual mode (via Bluetooth control)** and **automatic mode (maze solving / obstacle handling)**.

---

##  Features

*  Bluetooth control using mobile app
*  Manual movement (forward, backward, left, right)
*  Robotic arm control (servo motors)
*  Automatic mode for maze navigation
*  Ultrasonic sensors for obstacle detection
*  Smooth servo motion control

---

##  Hardware Components

* Arduino board
* Motor driver (L298N or similar)
* Ultrasonic sensors (HC-SR04)
* Servo motors
* Bluetooth module (HC-05 / HC-06)
* DC motors + wheels
* Power supply

---

##  Software & Libraries

* Arduino IDE
* Wire.h
* Adafruit_PWMServoDriver
* SoftwareSerial

---

##  Control System

The car is controlled via Bluetooth commands:

* `F` → Forward
* `B` → Backward
* `L` → Left
* `R` → Right
* Arm control via specific buttons

---

##  Modes

###  Manual Mode

* Controlled by user via mobile app
* Full control of movement and robotic arm

###  Automatic Mode

* Uses ultrasonic sensors
* Navigates maze / avoids obstacles

---

##  Repository Structure

```
Plaza_-2/
│── README.md
│── main_code.ino
│── assets/
```

---

##  Author

* Asmaa EL bnna

---

##  Notes

This project was developed for a robotics competition and demonstrates integration between hardware and software systems.
