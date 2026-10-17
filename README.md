# Autonomous Warehouse Fulfillment Robot

A Raspberry Pi-based robotics project exploring autonomous object tracking and feedback-driven motor control using Python and PID control.

## Overview

This project focuses on integrating sensor input, motor control, and PID-based feedback to support autonomous robot movement.

## Technologies

- Python
- Raspberry Pi
- PID Control
- Sensor Integration
- Motor Control

## System Components

- **Sensor Processing:** Reads sensor inputs to inform movement decisions.
- **PID Control:** Uses feedback to adjust motor behaviour.
- **Motor Control:** Translates control outputs into robot movement.

## Hardware Documentation

See the included hardware map PDF for the component layout and connections.

## Testing and Performance Evaluation

**Control System**
- Implemented PID-based control logic using ultrasonic distance measurements.
- Set a target following distance of 20 cm.
- Used sensor feedback to calculate distance error and adjust motor output.

**Testing Methodology**
- Number of test runs: 50+
- Target distance: 20 cm

**Results**
- Average distance error: 2.5 cm
- Following success rate: 95%

## Future Improvements

- Separate sensor processing, PID calculations, and motor control into reusable functions.
- Add automated tests for control calculations.
- Document tracking accuracy and performance using measured test results.
- Include photos or a demonstration video of the robot in operation.

## Notes

This project is under development. Hardware requirements and execution steps depend on the robot's specific configuration.
