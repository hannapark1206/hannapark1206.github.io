---
title: "Fixed-Wing Aerial Robot Sensing and Flight-Control Integration"
summary: "Flight-control integration, ROS/MAVLink data workflows, five-hole Pitot probe hardware, and wind-tunnel calibration for fixed-wing aerial robot testing."
date: 2024-10-01
tags:
  - Aerial Robotics
  - Flight Control
  - Aerodynamic Sensing
  - ROS/MAVLink
  - Wind-Tunnel Testing
---

## Overview

This project focuses on preparing a fixed-wing aerial robot for controlled flight experiments by integrating flight-control hardware, onboard computation, actuator control, aerodynamic sensing, and ground-station communication.

The system combines a fixed-wing aircraft, custom five-hole Pitot probe hardware, pressure sensing, motion capture, and ROS/MAVLink data workflows to support flight testing and aerodynamic measurement.

## My Role

I worked on the sensing, flight-control integration, and experimental setup side of the system.

My contributions included integrating hardware across the aircraft and ground-station system, setting up communication and data workflows, supporting manual override for testing, synchronizing motion-capture data, and designing five-hole Pitot probe hardware for flow measurement.

## System Integration

The flight-test system brought together multiple hardware and software components:

- Cube Orange+ flight controller
- Jetson onboard computer
- Teensy microcontroller
- Servo actuator control
- NUC ground station
- QGroundControl / Mission Planner
- MAVLink / MAVROS communication
- ROS-based data collection
- OptiTrack motion capture

The goal was to make the aircraft test-ready while keeping the system reliable enough for manual override, debugging, and experimental data collection.

## Five-Hole Pitot Probe Design

The aerodynamic sensing subsystem used custom five-hole Pitot probe hardware to measure local pressure and flow-angle information.

I worked on probe geometry, housing design, sensor integration, and calibration planning. The design process included:

- Studying modified ellipsoidal Pitot probe geometry
- Using a 4:1 ellipsoidal nose profile
- Choosing a flat-tip geometry to reduce suction peak effects
- Considering hole sizing, burrs, and fabrication limits
- Evaluating tubing bends and pressure-loss effects
- Designing probe housings and sensor layouts
- Preparing for wind-tunnel calibration

## Data and Testing Workflow

The system was designed to collect synchronized data from multiple sources, including pressure sensors, flight-controller telemetry, IMU data, actuator commands, and motion-capture tracking.

Important testing goals included:

- Reliable telemetry and command links
- ROS/MAVLink data retrieval
- Manual override during free-flight testing
- Wind-tunnel calibration of the sensing hardware
- Real-time aircraft tracking using OptiTrack
- Post-test analysis of pressure, motion, and flight-control data

## Skills Used

- Aerial robotics
- Flight-control integration
- Aerodynamic sensing
- Five-hole Pitot probe design
- ROS Noetic
- MAVLink / MAVROS
- QGroundControl / Mission Planner
- Cube Orange+
- Jetson
- Teensy
- OptiTrack
- Wind-tunnel testing
- Sensor integration
- Hardware debugging

## Media

Photos, CAD screenshots, calibration plots, and test videos will be added here.
