
# Navigation in GPS-Denied Environments

## Overview
This project implements a sensor-fusion-based localization system for autonomous
navigation in GPS-denied environments using IMU and visual odometry.

## Key Concepts
- Extended Kalman Filter (EKF)
- Visual Odometry
- Sensor Fusion
- Drift Compensation

## Technologies Used
- Python
- OpenCV
- IMU Sensors
- FAST & ORB Feature Detection

## System Workflow
1. IMU data provides motion estimation
2. Visual odometry estimates pose from camera frames
3. EKF fuses both to reduce drift
4. Trajectory is recorded and mapped

## Results
- Improved localization accuracy in GPS-denied scenarios
- Stable trajectory tracking with reduced drift

 ## Documentation
📄 [Project Presentation](Navigation_in_GPS_Denied_Environment.pdf)
