# Bus and Truck Drunk Driving Alert System

Overview

The **Bus and Truck Drunk Driving Alert System** is an Arduino-based embedded system designed to improve road safety by preventing vehicles from operating when the driver is under the influence of alcohol. The system continuously monitors the driver's breath using an **MQ-3 alcohol sensor**. If the detected alcohol level exceeds a predefined threshold, the system triggers an alarm, displays a warning message, and disables the vehicle's ignition using a relay.

This project aims to reduce accidents caused by drunk driving and demonstrates the practical application of embedded systems in automotive safety.


## Features

- Real-time alcohol detection
- Automatic engine lock using relay
- Audible buzzer alert
- LCD warning display
- Low-cost and reliable design
- Easy to install and operate


 Hardware Components

- Arduino Uno
- MQ-3 Alcohol Sensor
- 16×2 LCD Display (I2C)
- Relay Module
- Buzzer
- DC Motor (Engine Simulation)
- Breadboard
- Jumper Wires
- 5V Power Supply



Software Used

- Arduino IDE
- Embedded C



working Principle

1. The MQ-3 sensor continuously detects alcohol concentration.
2. The Arduino reads the sensor value.
3. If the alcohol level exceeds the predefined threshold:
   - The buzzer is activated.
   - A warning message is displayed on the LCD.
   - The relay disconnects the motor, simulating engine shutdown.
4. If no alcohol is detected, the vehicle continues to operate normally.


Applications

- Commercial buses
- Heavy trucks
- School buses
- Fleet management
- Public transportation
- Industrial vehicles

 Future Enhancements

- GPS location tracking
- GSM-based SMS alerts
- IoT cloud monitoring
- Face recognition-based driver authentication
- Mobile application integration
- Data logging and analytics


Skills Demonstrated

- Embedded Systems
- Embedded C Programming
- Arduino Programming
- Sensor Interfacing
- Relay Control
- Automotive Safety Systems
- Hardware Integration
- Electronics Prototyping



 Authors
- Mayur Dhang

