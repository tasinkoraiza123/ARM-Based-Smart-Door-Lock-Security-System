# ARM-Based Smart Door Lock & Security System

An STM32-based smart door lock that uses PIN authentication, motion detection, and embedded hardware to improve door security.

## Project Overview

- Developed and tested a PIN-based smart door lock integrating sensors and embedded hardware.
- Identified and debugged a sensor malfunction that caused incorrect motion detection during system startup.
- Tested system functionality and edge cases to evaluate reliability.


### Features
- **PIN Authentication:** Unlocks the door when the correct PIN is entered.
- **OLED Display:** Displays PIN prompts, access status, and system lock messages.
- **PIR Motion Detection:** Activates the system when someone approaches.
- **Wrong Password Protection:** Locks the system for 15 seconds after three incorrect attempts and activates the buzzer.
- **Servo Motor Control:** Controls door locking and unlocking.

### Hardware Components
- STM32F103C8T6 (Blue Pill)
- 4×4 Matrix Keypad
- SSD1306 OLED Display (I²C)
- HC-SR501 PIR Motion Sensor
- Servo Motor
- Active Buzzer

### Technologies
- Embedded C
- STM32CubeIDE
- STM32CubeMX
- GPIO, PWM, and I²C

### Working Principle
The PIR sensor detects approaching motion and activates the OLED display. The user enters a PIN using the keypad. If the PIN is correct, the servo unlocks the door. The reed switch detects the door's status, allowing automatic relocking. Three incorrect PIN attempts trigger a 30-second security lockout with a buzzer alert.


## Project Proposal & Report:



## Team Members

1. Tasfin Koraiza Boishakhi — 2211528042
2. Tasfia Samrin — 2211249042
3. Mosroor Mofiz Arman — 1921079642

## Course Information

- **Course:** CSE331L — Microprocessor Interfacing and Embedded System Lab
- **Institution:** North South University
- **Semester:** Summer 2026
- **Faculty:** Mr. Md. Ragibur Rahman [RQN]
