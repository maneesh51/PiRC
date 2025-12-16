# Physical Machine Learning with Water-Based Reservoir Computing

This repository contains the control and experimental code for a **water-based physical Reservoir Computing (RC) device**, where information is encoded through surface ripples generated in water using servo motors.

## Project Background
This work explores **physical machine learning**, using water as a dynamical medium for Reservoir Computing.

- **Additional project details:** 1. [https://www.tu.berlin/cpsme/studium-lehre/lehrveranstaltungen/x-student-research-group]
  2. [https://maneesh51.github.io/projects/scikit/]

<p align="center">
  <img src="https://github.com/maneesh51/PiRC/blob/0412d9d5b5eecdb3f5e7e32780aaa05eded93ee1/IMG_1419.jpg" width="600">
</p>

## Repository Overview
- The code controls **two servo motors** to implement an **XOR task**:
  - `[0, 0]` → No motor activation  
  - `[0, 1]` → Motor 1  
  - `[1, 0]` → Motor 2  
  - `[1, 1]` → Motors 1 and 2  
- Input information is **encoded as ripples on the water surface** inside a container.
- The resulting spatio-temporal water dynamics are **recorded using an overhead camera** and later processed for computation.

## 1. Experimental Setup
The system is controlled using a **Raspberry Pi 3**, connected as follows:

- Raspberry Pi → Servo Motors    
- Raspberry Pi ↔ Camera, HDMI display, keyboard (USB), mouse (USB)

## 2. Hardware Components
- Raspberry Pi 3B  
- PCA9685 servo driver  
- Servo motors  
- Power bank / batteries  
- High-speed camera (e.g., Angetube Autofocus)  
- HDMI cable, keyboard, mouse, display  

## 3. Useful Resources
- Controlling multiple servo motors with Raspberry Pi and PCA9685:  
  [https://tutorials-raspberrypi.de/mehrere-servo-motoren-steuern-raspberry-pi-pca9685/]
