# Two-Wheel Drive Robot Control using WASD Keys

## Overview
This project demonstrates how to control a two-wheel drive robot using keyboard inputs (W, A, S, D). The robot receives commands via serial communication and moves accordingly.

## Controls

W - Move Forward  
S - Move Backward  
A - Turn Left  
D - Turn Right  

## Working Principle
- The robot receives commands from a computer .
- Each key press is sent as a character through serial communication.
- Arduino reads the input and controls the motors.
- A motor driver (L298N) is used to drive the motors.

## Components Required
- Arduino Uno 
- Motor Driver (L298N)
- Jumper Wires

## Circuit Connections
- Motor driver input pins connected to Arduino digital pins
- Motor driver output pins connected to motors
- Enable pins connected to PWM pins (optional for speed control)
- Power supply connected to motor driver

