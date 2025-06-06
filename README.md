# LEGO-Based Mobile Robot Navigation and Structure Identification

## Project Overview

This project involves building a LEGO-based mobile robot that autonomously navigates a predefined circular path, using an **ultrasonic sensor** to measure the distance to objects and an **IR sensor** to follow the yellow path. The robot uses motors that are part of the LEGO kit for movement. It classifies the shape placed at the center of the circular path based on the distance measured, determining whether the object is a **Square**, **Circle**, **Triangle**, or **No Object**.


## Objective

- **Autonomous Navigation**: The robot autonomously follows a circular path using the IR sensor for line-following.
- **Shape Detection**: The robot identifies an object placed at the center of the circle and classifies it.
- **Shape Classification**: Based on the distance measured by the ultrasonic sensor, the robot classifies the shape into **Square**, **Circle**, **Triangle**, or **No Object**.

## Features

- **Circular Path Navigation**: The robot autonomously follows a circular path with a radius of 1.3 meters.
- **Shape Classification**: The robot classifies the object based on distance using the ultrasonic sensor:
  - **No Object**: If the `Final Distance > 50`.
  - **Square**: If the `Final Distance > 20`.
  - **Circle**: If the `Final Distance > 10`.
  - **Triangle**: If the `Final Distance <= 10`.
- **Path Following**: The IR sensor detects the yellow path and allows the robot to follow it.
- **Visual Feedback**: Status lights change based on the detected shape.

## Hardware Components

- **LEGO Mindstorms Core Set**: Used for building the robot and controlling movement with internal motors.
- **Ultrasonic Sensor**: Used to measure the distance to the object at the center.
- **IR Sensor**: Used to detect the yellow line on the path and help the robot follow it.
- **LEGO Motors**: Motors already integrated into the LEGO Mindstorms kit for movement control.
- **Microcontroller**: Built-in controller in the LEGO kit that manages the sensors and motors.
