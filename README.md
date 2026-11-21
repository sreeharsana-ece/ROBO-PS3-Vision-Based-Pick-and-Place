# ROBO:PS3 – Vision-Based Object Detection and Robotic Pick-and-Place

## Project Overview
ROBO:PS3 is a proposed intelligent robotic pick-and-place system that uses computer vision, deep learning and ROS 2 to identify objects and perform automated material handling.

## Problem Statement
Traditional robotic systems depend on predefined object positions, making it difficult to handle randomly placed objects with different shapes, sizes and orientations.

## Proposed Solution
Our solution uses an RGB-D camera to capture objects and a YOLO-based model to detect them. Depth information estimates their 3D positions and orientations. ROS 2 TF2 transforms the coordinates, while MoveIt 2 plans suitable robotic movements. A robotic arm with a gripper then picks and places objects at their assigned destinations.

## Technologies Proposed
- Python
- ROS 2
- YOLO
- OpenCV
- MoveIt 2
- Gazebo Simulation
- RGB-D Camera

## Expected Outcome
An adaptive robotic system capable of detecting randomly positioned objects and performing intelligent pick-and-place operations for industrial automation.

## Project Presentation Video
[Watch ROBO:PS3 Project Presentation](https://youtu.be/MokU6G7eTtg)

## Project Status
Proposed solution – development and simulation planned.

## Application Areas
- Manufacturing industries
- Warehouse automation
- Industrial material sorting
- Robotic handling systems
