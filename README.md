# 6DOF Robot Arm Simulation – ABB IRB 4600-40/2.55

A realistic **Webots** simulation of the ABB IRB 4600-40 industrial robot arm with 6 degrees of freedom.

<p align="center">
  <img src="Media\Pictures\8.png" alt="IRB 4600 in CoppeliaSim" width="70%"/>
  <br><em>Simulation of ABB IRB 4600-40/2.55</em>
</p>

## Table of Contents

- [6DOF Robot Arm Simulation – ABB IRB 4600-40/2.55](#6dof-robot-arm-simulation--abb-irb-4600-40255)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Robot Specifications](#robot-specifications)
    - [Working Range](#working-range)
  - [Technologies](#technologies)
  - [Repository Structure](#repository-structure)
  - [📸 Simulation Results](#-simulation-results)
    - [Simulation View](#simulation-view)
    - [Robot View](#robot-view)
    - [Main Menu](#main-menu)
    - [Move joints](#move-joints)
    - [Move End-Effector](#move-end-effector)
    - [Draw Circle](#draw-circle)
    - [Draw Square](#draw-square)
    - [Draw Rectangle](#draw-rectangle)
    - [Imitate](#imitate)
  - [Authors](#authors)

## Overview

This project contains a detailed simulation model of the **ABB IRB 4600-40/2.55** — a popular 6-axis industrial robot — created and tested in **Webots**.

It can be used for:

- Robotics education
- Kinematics & dynamics studies
- Path planning & trajectory generation experiments
- Controller development & testing
- Visualization of industrial robot behavior

## Features

- Accurate 6-DOF kinematic model
- Realistic joint limits
- High-quality textures & visual appearance
- Multiple ready-to-use simulation scenes
- Basic joint & TCP control examples
- Support for Python scripts

## Robot Specifications

| Parameter              | Value                     |
|------------------------|---------------------------|
| Model                  | ABB IRB 4600-40/2.55      |
| Number of axes         | 6                         |
| Maximum payload        | 40 kg                     |
| Maximum reach          | 2550 mm                   |
| Pose repeatability     | 0.06 mm                   |
| Weight                 | ~435–465 kg               |
| Mounting options       | Floor, inverted, tilted   |
| Typical controller     | IRC5 (simulated behavior) |

<p align="center">
  <img src="Media\Pictures\6.png" alt="Working Range" width="40%"/>
</p>


> Source: official ABB documentation

## Technologies

- **Webots** (recommended: R2025a or newer)
- Python script
- Textures & 3D model preparation tools

## Repository Structure

6DOF-Robot-Arm-Simulation-IRB-4600-40-/ 

├── Data Sheet/         # Technical datasheet

├── Media/              # Pictures, video

├── controllers/        # Control scripts (Python)

├── textures/           # Texture files used in the model

├── worlds/             # Simulation scenes (.wbt)

└── README.md

## 📸 Simulation Results

<p align="center">
  <img src="Media\Pictures\9.png" alt="Simulation View" width="70%"/>
</p>

<div align="center">
  <video src="https://github.com/Mohammad-Mahdi-Khademi/6DOF-Robot-Arm-Simulation-IRB-4600-40-/main/Media/Videos/Simulation%20Environment.mp4" controls width="80%" preload="metadata"></video>
  <p>Simulation Environment</p>
</div>

<p align="center">
  <img src="Media\Pictures\8.png" alt="Robot View" width="70%"/>
</p>

<p align="center">
  <img src="Media\Pictures\10.png" alt="Main Menu" width="70%"/>
</p>

<p align="center">
  <img src="Media\Pictures\11.png" alt="Move joints" width="70%"/>
</p>

<div align="center">
  <video src="https://github.com/Mohammad-Mahdi-Khademi/6DOF-Robot-Arm-Simulation-IRB-4600-40-/main/Media/Videos/Moving%20Joints.mp4" controls width="80%" preload="metadata"></video>
  <p>Moving Joints</p>
</div>
<p align="center">
  <img src="Media\Pictures\12.png" alt="Move End-Effector" width="70%"/>
</p>

<div align="center">
  <video src="https://github.com/Mohammad-Mahdi-Khademi/6DOF-Robot-Arm-Simulation-IRB-4600-40-/main/Media/Videos/Tracking.mp4" controls width="80%" preload="metadata"></video>
  <p>Tracking</p>
</div>

<p align="center">
  <img src="Media\Pictures\13.png" alt="Draw Circle" width="70%"/>
</p>

<p align="center">
  <img src="Media\Pictures\14.png" alt="Draw Square" width="70%"/>
</p>

<p align="center">
  <img src="Media\Pictures\15.png" alt="Draw Rectangle" width="70%"/>
</p>

<p align="center">
  <img src="Media\Pictures\16.png" alt="Imitate" width="70%"/>
</p>

<div align="center">
  <video src="https://github.com/Mohammad-Mahdi-Khademi/6DOF-Robot-Arm-Simulation-IRB-4600-40-/main/Media/Videos/Imitation.mp4" controls width="80%" preload="metadata"></video>
  <p>Imitation</p>
</div>
---
## Authors

- **Mohammad Mahdi Khademi**
- **Negar Naghavian**

Supervised by: Dr. Seyed Hassan Zabihifar

---
