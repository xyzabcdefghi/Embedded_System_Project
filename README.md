# Embedded_System_Project
Overview
This project implements a proximity detection system using Embedded C and LPC1768 microcontroller. The system utilizes an ultrasonic sensor to detect the distance of nearby obstacles. When an obstacle is detected within a range of less than 10 cm, the system activates a buzzer and illuminates LEDs to indicate the presence of the obstacle.

# Components
LPC1768 microcontroller board,
Ultrasonic sensor (HC-SR04),
Buzzer,
LEDs,
Resistors,
Breadboard,
Connecting wires

# Setup
Connect the LPC1768 microcontroller board to your development environment (e.g., Keil µVision).
Connect the ultrasonic sensor, buzzer, and LEDs to the appropriate GPIO pins on the LPC1768 board.
Ensure that the necessary libraries and drivers are installed and configured in your development environment.
Compile and upload the project code (main.c) to the LPC1768 board.
Usage
Power on the LPC1768 board.
Place the ultrasonic sensor in a location where it can detect obstacles.
When an obstacle is detected within a range of less than 10 cm, the buzzer will activate, and the LEDs will illuminate.
Adjust the sensitivity and threshold values as needed in the code (main.c) to customize the detection range and behavior.
