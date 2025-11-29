# TortoiseBot Intelligent Systems Lab

This repository documents a journey to become an **AI & Intelligent Automation Solution Architect with a focus on Robotics**.

Using a custom-built TortoiseBot (Raspberry Pi 4, Camera, LiDAR, IMU, L298N motor driver), I implement a series of progressively complex systems:

- Low-level motor and sensor control
- ROS2-based modular software architecture
- Perception pipelines with Camera, LiDAR, and IMU
- Autonomous navigation with Nav2
- Edge AI with on-device inference
- Integration of Robotics with Intelligent Automation (UiPath)

Each `weekXX_*` folder contains:

- **Problem statement**
- **Architecture and design**
- **ROS2 / Python code**
- **How to run**
- **Learn (from an architect's perspective)**

## Repository Structure

- `docs/` – Architecture diagrams, technical notes, and the roadmap
- `hardware/` – Bill of materials, wiring diagrams, and mechanical assembly notes
- `week01_modular_motor_system/` – GPIO-based motor control and modular movement architecture
- `week02_ros2_nodes_basics/` – ROS2 publisher/subscriber fundamentals
- `week03_camera_perception_pipeline/` – Camera + OpenCV + ROS2 perception pipeline
- ...
- `week11_rpa_robot_integration/` – UiPath + ROS2 proof-of-concept for orchestrated robotics
- `capstone_autonomous_robot_system/` – Full-stack autonomous robot: perception, navigation, edge AI, and orchestration

## Technology Stack

- **Robotics / Middleware**: ROS2 (Humble), Nav2, RViz2
- **Compute**: Raspberry Pi 4
- **Perception**: Raspberry Pi Camera, LiDAR, IMU
- **AI/ML**: Python, OpenCV, PyTorch/TensorFlow (for edge AI)
- **Automation**: UiPath (for robot workflow orchestration)
- **Languages**: Python, (C++ optional)
- **Tools**: Git, VS Code, SSH, Linux


