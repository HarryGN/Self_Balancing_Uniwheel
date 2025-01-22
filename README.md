# Self-Balancing Uniwheel Project

This project involves building a self-balancing uniwheel powered by a customized driver board. The uniwheel uses an **ESP32** microcontroller and is capable of driving two **BLDC (Brushless DC) motors**. The system uses an **IMU (MPU6050)** sensor for balancing and orientation sensing.

## Features
- **ESP32 Microcontroller**: Controls the uniwheel's balancing and motor control.
- **BLDC Motors**: Two motors for driving the uniwheel.
- **MPU6050 IMU Sensor**: Provides real-time data for balancing and stability.
- **Customized Driver Board**: Designed specifically for this project to control the motors and handle power distribution.

## Schematic

Below is the schematic diagram for the uniwheel system:

![Schematic](https://github.com/user-attachments/assets/492c3242-f155-4b34-b9de-f86ba90601f1)

## Components Used
- **ESP32 Microcontroller**: A powerful and versatile microcontroller with built-in Wi-Fi and Bluetooth capabilities.
- **MPU6050 IMU Sensor**: A 6-axis sensor used for detecting orientation and motion, crucial for balancing.
- **BLDC Motors**: Brushless DC motors used for driving the uniwheel.
- **Customized Driver Board**: A custom-designed board for controlling the motors and managing power.
  
## How It Works
The uniwheel system uses feedback from the MPU6050 IMU sensor to maintain balance. The ESP32 processes the sensor data and adjusts the power sent to the BLDC motors to keep the uniwheel upright.

- The **MPU6050** sensor continuously monitors the tilt angle of the uniwheel.
- The **ESP32** processes the sensor data and sends commands to the **driver board** to adjust the motor speeds.
- The **BLDC motors** adjust the uniwheel's speed and direction to maintain balance.

## Images

Here are some images of the project setup:

![Uniwheel Setup](https://github.com/user-attachments/assets/63501c74-0296-4fa6-9d12-41ae8d6e8e9d)

![Driver Board](https://github.com/user-attachments/assets/2bdda0ba-70a3-4442-abec-d788c561cff9)

## Getting Started

To get started with this project, you will need the following components:
- **ESP32 Microcontroller**
- **MPU6050 IMU Sensor**
- **Two BLDC Motors**
- **Customized Driver Board**
- **Power Supply** (suitable for your motor and ESP32)

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/HarryGN/Self_Balancing_Uniwheel.git
