# HomeBoy 2.0

A smart home control system built for MCD1160 (Assignment 2), using Arduino.

<img width="428" height="257" alt="image" src="https://github.com/user-attachments/assets/594051c2-348f-4899-83c7-1442f8f9979a" />

## What it does

- Password-protected access with a 5-attempt lockout
- Servo-controlled locks for two doors (front door, kitchen door)
- Ultrasonic-sensor-based intruder alarm that triggers when movement is detected while armed
- Motorised window with position tracking (open/close to set percentages)
- Analog and digital control over room lighting (bedroom, living room, bathroom)
- Temperature display via DHT11 sensor with Celsius/Fahrenheit toggle
- LCD and serial menu interface for navigating all features

## Hardware

- Arduino board
- 16x2 LCD (I2C)
- 2x servo motors (door locks)
- DC motor + H-bridge driver (window)
- Ultrasonic distance sensor
- DHT11 temperature sensor
- Piezo buzzer
- LEDs for room lighting

## Notes

Team assignment for a university electronics unit. Wrote the full firmware solo; a teammate handled the 3D-printed enclosure and physical hardware build.
