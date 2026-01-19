# prosthetic-hand-prototype
A 3D-printed prosthetic hand with Arduino PID control.

# Prosthetic Hand with PID Control 

## Project Overview
This project focuses on the design and fabrication of a fully articulated prosthetic hand. The system bridges mechanical engineering and embedded systems, utilizing **Onshape** for kinematic design and an **Arduino-based closed-loop PID controller** for precise actuation. The goal was to replicate human grasp mechanics with variable grip strength and high positional accuracy.

## Key Engineering Features

### Mechanical Architecture & Kinematics
* **Friction Reduction:** Optimized joint geometry through iterative physical testing, achieving a **30% reduction in joint friction**.
* **Tolerance Analysis:** Implemented precise **0.3mm clearance gaps** in all hinge designs to balance structural rigidity with smooth rotation.
* **Rapid Prototyping:** Designed in **Onshape** with a focus on DFM (Design for Manufacturing) to ensure printability without requiring support structures in critical joint areas.

### Embedded Systems & Control Logic
* **Closed-Loop Control:** Programmed a custom **PID (Proportional-Integral-Derivative) algorithm** in C++ to eliminate motor jitter and overshoot.
* **High-Speed Actuation:** Achieved a grasp response time of **under 200ms**, allowing for near-instantaneous reaction to user input.
* **Precision Handling:** Attained joint positioning accuracy within **2 degrees** of target angles, enabling the handling of delicate objects without crushing them.

## Technical Specifications
* **CAD Software:** Onshape
* **Microcontroller:** Arduino Uno (ATmega328P)
* **Material:** PLA

---
*Created by [Your Name]*
