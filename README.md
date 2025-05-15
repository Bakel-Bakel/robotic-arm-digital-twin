# 🤖Robotic Arm Digital Twin – Unity + MATLAB Integration

## 🚀 Project Overview

This project aims to create a **virtual robotic arm** in Unity, simulate its motion using kinematics, and control it using MATLAB via real-time communication. The pipeline integrates 3D modeling (SolidWorks → Blender → Unity), DH parameter setup, MATLAB Robotics Toolbox, and Unity scripting with C#.


![Screenshot from 2025-05-15 08-11-35](https://github.com/user-attachments/assets/0809f81f-b657-4d42-a62b-8ef46266b34d)

The final objective is to implement an **interactive, intelligent robotic system** that can:
- Pick and place objects
- Sort by color using vision from Unity to MATLAB
- Operate on a conveyor belt system with sensors and feedback

## 🎯 What I’m Learning

- Importing and configuring robotic models in Unity
- Defining revolute joints and reference origins in Blender
- Building and testing kinematic chains using the Denavit–Hartenberg (DH) convention
- Real-time robotic arm control using MATLAB scripts
- C# and MATLAB communication (image transfer, data sync)
- Conveyor belt simulation with sensor-triggered responses

## 🧩 Project Parts

### ✅ Part 1: Robot Import & Joint Setup
- Creating Unity project
- Importing model from SolidWorks
- Joint configuration in Blender
- Final model assembly in Unity

### ✅ Part 2: Kinematics & MATLAB Control
- Creating the DH-Table
- Kinematic diagram of the Parol6 arm
- MATLAB control using Robotics Toolbox
- Gripper control and object grabbing

### ✅ Part 3: Vision & Sorting by Color
- Sending Unity camera feed to MATLAB
- Sorting colored objects using MATLAB
- Understanding C#-MATLAB data flow

### ✅ Part 4: Conveyor Belt & Feedback
- Adding and controlling a conveyor in Unity
- Object tracking on conveyor
- Sensor programming and MATLAB integration

## 📦 Dependencies

- [Unity 2021.3+](https://unity.com/)
- [Blender](https://www.blender.org/)
- [MATLAB Robotics Toolbox](https://petercorke.com/toolboxes/robotics-toolbox/)
- SolidWorks (or other CAD tools)
- C# for Unity scripting
- TCP/UDP or MATLAB Engine API for communication

## 📸 Preview



https://github.com/user-attachments/assets/1d6db898-7c59-4e74-aa3e-e214d7ad318e





