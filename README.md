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

## Methods and Analysis

**Data Processing**
- Loaded student records from CSV files and converted values to appropriate numeric types where possible.
- Filtered records by selected student attributes and calculated average grades using FallGrade and WinterGrade.

**Visualization**
- Used Matplotlib to generate histograms for numerical attributes and bar charts for categorical attributes.

**Relationship Analysis**
- Grouped students by selected attributes and calculated average grades for each group.
- Applied NumPy polynomial fitting to model relationships between student attributes and average grades.

**Dataset**
- Number of records analyzed: 500+
- Tools: Python, NumPy, Matplotlib

## Future Improvements

- Separate sensor processing, PID calculations, and motor control into reusable functions.
- Add automated tests for control calculations.
- Document tracking accuracy and performance using measured test results.
- Include photos or a demonstration video of the robot in operation.

## Notes

This project is under development. Hardware requirements and execution steps depend on the robot's specific configuration.
