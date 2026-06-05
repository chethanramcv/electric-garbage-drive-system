# Electric Garbage Drive System

An automated prototype for smart waste collection using microcontroller-based motor control. Built as a final year project at Atria Institute of Technology.

## Problem
Manual garbage collection is inefficient and unhygienic in high-traffic areas. This system automates the drive mechanism to reduce human intervention.

## Solution
- Uses [ATmega328P/Arduino Uno] to control DC motor based on sensor input
- Embedded C code for motor direction, speed, and obstacle detection
- Tested under 3 load conditions: 0kg, 2kg, 5kg

## Tech Stack
- **Language**: Embedded C
- **Hardware**: ATmega328P, DC Motor, Motor Driver L298N, IR Sensors
- **Tools**: Arduino IDE, Proteus/Multisim for simulation

## How to Run
1. Open `main.c` in Arduino IDE
2. Select board: Arduino Uno
3. Upload to board and connect hardware as per `circuit_diagram.pdf`
4. Power on and test with varying loads

## Demo
[Add a 15s video/GIF if you have it. If not, delete this section]

## Learnings
- Hardware-software integration and debugging
- Reading datasheets for motor drivers and sensors
- Basic project documentation and version control with Git

## Author
Chethan Ram C V 
