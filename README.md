# 2WD Robot RC using Arduino
Build Status ↗ ↗

This repository contains the source code and documentation for a 2WD Robot RC using Arduino. The robot is controlled through a remote control and can move forward, backward, turn left, turn right, and stop.

# Hardware Requirements
The following hardware is required to build this project:

# Arduino UNO or similar board
L298N motor driver
Two DC motors
HC-05 Bluetooth module
9V battery
Breadboard and jumper wires
Remote control (such as a smartphone with Bluetooth)
# Installation
To install the software, follow these steps:

Clone this repository: git clone https://github.com/ahmed-eldesoky284/2WD-Rocto-RC
Connect the hardware components as shown in the diagram in the docs directory.
Upload the 2wd-robot-rc.ino sketch to the Arduino board using the Arduino IDE.
Install a Bluetooth terminal app on your remote control device.
Pair the HC-05 Bluetooth module with the remote control device.
Open the Bluetooth terminal app and connect to the HC-05 module.
Use the app to send commands to the robot.
# Usage
To use the robot, follow these steps:

Turn on the robot and the remote control device.
Open the Bluetooth terminal app and connect to the HC-05 module.
Send commands to the robot using the app. The commands are:
F: Move forward
B: Move backward
L: Turn left
R: Turn right
S: Stop
# License
This project is licensed under the MIT License. See the LICENSE file for details.
