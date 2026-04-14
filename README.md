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
- Hobby gearmotor

## Circuit Connections
- Motor driver input pins connected to Arduino digital pins
- Motor driver output pins connected to motors
- Power supply connected to motor driver

## Challenges Faced (Syntax & Understanding)

- Initially did not know how to write the syntax for `Serial.begin()` and `Serial.read()`.
- Took time to understand how serial communication works in Arduino.
- Faced confusion while writing correct syntax for reading inputs.
- Had difficulty understanding how the L298N motor driver works.
- Took time to learn how to write proper code to control motors using the driver.
- Used 'int' instead of 'char' for reading for raeding seriel input
- Forgot to use quotation for characters
