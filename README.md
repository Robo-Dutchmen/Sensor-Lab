# Sensor Lab

![Our Final Circuit](media/circuit.jpg)

## Description
This repository contains our code for Sensor Lab for Mechatronics Design 2020. For this lab, we are integrating three sensors: an IR distance sensor, an Ultrasonic distance sensor, and a potentiometer. Our demonstration shows a system in which the potentiometer will alter a threshold distance in which the two distance sensors must be under. Meeting this distance constraint will turn on a red LED and green LED for the IR sensor and Ultrasonic sensor respectively.

## Installation

### GUI
To ensure proper functionality of the GUI, install Anaconda (https://www.anaconda.com/distribution/), then ensure that ```pyserial``` is installed in Anaconda Navigator. To check, open up Anaconda Navigator, go to Environments, change the dropdown menu to All instead of Installed, then search for ```pyserial```. Check the box if not already checked and proceed with the installation.

### Arduino
To wire up the Arduino, follow the wiring in the image below:
![Our Circuit Wiring](media/wiring.jpg)

## Deployment
1. Connect the Arduino Uno to the computer.
2. On the Arduino IDE, check the Serial Port of the connected Arduino.
3. On ```gui.py```, ensure that the Serial Port matches that found in the Arduino IDE.
4. Run ```python gui.py``` on the Anaconda terminal.
