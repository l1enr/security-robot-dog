# Security Robot Dog

## Project Overview
The Security Robot Dog is a conceptual 3D model designed using Tinkercad. It represents a robotic dog developed for security and surveillance purposes. The model features a simple four-legged structure with a front-mounted camera and built-in Wi-Fi connectivity.

## Features
- Four-legged robotic design.
- Front-mounted security camera.
- Built-in Wi-Fi connectivity.
- Servo motors for the leg joints.
- Four leg joints (4 DOF).
- The center of gravity is located near the middle of the robot body to improve stability.
- The robot uses a simple Crawl Gait, where one leg moves at a time while the other three legs remain on the ground.
- The main motion is rotational motion produced by the servo motors, allowing the leg joints to move with angular oscillation.
- Lightweight and compact structure suitable for educational purposes.

## Main Components
- Robot body
- Four legs
- Four leg joints
- Front camera
- Built-in Wi-Fi module

## Estimated Joint Torque
A simple torque estimation was performed for one leg joint.

Assumptions:
- Robot mass: approximately 1 kg
- Load per leg: approximately 2.45 N
- Distance from the joint to the leg center: 0.08 m

Torque = Force × Distance

Torque = 2.45 × 0.08 ≈ 0.2 N·m

This torque can be provided by a small servo motor.

## Expected Mechanical Challenges
- Limited walking speed.
- Reduced stability on uneven surfaces.
- Servo motors must provide enough torque for stable movement.

## Software Used
- Tinkercad

## Project Preview

![Security Robot Dog](RobotDog.png)
