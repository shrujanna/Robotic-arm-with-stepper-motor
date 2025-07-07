# Robotic-arm-with-stepper-motor


This project showcases a simple **robotic arm** built using a **28BYJ-48 stepper motor**, controlled by an **Arduino Nano**, and operated wirelessly using a **TV remote (TSOP sensor)**. An **additional IR sensor** is used to control the **gripper mechanism**, allowing it to pick and place objects based on sensor input.

![WhatsApp Image 2025-07-07 at 20 55 03_ae9c99f8](https://github.com/user-attachments/assets/2557a017-5d29-4b42-829e-386ce08f14ec)




### Features

* **Wireless control** using standard TV remote via TSOP sensor.
* **Gripper automation** using IR proximity sensor to detect object presence.
* **Precise arm movement** with stepper motor control using ULN2003 driver.
* Compact setup using **Arduino Nano** for real-time control.

###  Use Case

This arm can demonstrate basic automation and object manipulation, and serves as a learning tool for:

* Stepper motor control
* Sensor integration
* Signal decoding (remote)
* Real-world actuator applications

###  Components Used

* Arduino Mego
* 28BYJ-48 Stepper Motor with ULN2003 Driver - 2 units
* TSOP1738 IR Receiver Module (for TV remote) - 1 unit
* IR Proximity Sensor - 1 unit 
* Jumper wires, breadboard, power supply
* SG90 Servo motor - 1 unit

###  How It Works

* **Remote Input:** Pressing buttons on the TV remote sends IR signals, which are decoded by the Arduino to move the arm.
* **Stepper Control:** The stepper motor moves in precise steps to rotate the arm in desired directions.
* **Gripper Logic:** The IR sensor detects when an object is in range and activates the gripper to grab/release it.

