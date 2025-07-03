# rosGhost2025 - Future Engineers WRO 2025

## 👥 Team Introduction
The rosGhost team is integrated by Alexis Quintero, Jose Filos, and Fiorella Campos, representing Colegio San Vicente de Paúl in Santiago, Panama, in the Future Engineers competition.

## 🛠️ Engineering Materials
This repository contains engineering materials for a self-driven vehicle model participating in the WRO Future Engineers competition in the 2025 season.

### Materials to Build Our Robot:
- 1 Lego Inventor Large Hub 88016  
- 1 Large Angular Motor (connected to port B)  
- 1 Medium Angular Motor (connected to port A)  
- 3 Technic Distance Sensors (connected to ports D, E, and F)  
- 1 Rechargeable battery 7.4V 2100mAh  
- Integrated gyroscope  
- 3D modeling designs for assembly  
- Building instructions  

---

## 🚗 Robot Structure and Design
The main design idea was developed by our team using two sources as guidelines: M.V.P and Anton's Mindstorms Hot Rod.  

We used the Studio 2.0 application to create and 3D model all parts found in the `models/` directory.

---

## 🔌 Components Assembly and Operating Diagram
- The `schemes/` directory contains:  
  - A connection diagram showing all port assignments.  
  - A process diagram detailing the robot's actions.  
  - A list and description of electronic components used.  

---

## 💻 Programming Code
- The `scr/` directory contains the main source code created using LEGO Inventor Mindstorms' block-based system and Python.  
- All programming was done by our team.

---

## 📂 Repository Contents
- `models/` — 3D modeled files for robot assembly.  
- `other/` — Additional files such as operation processes and execution details.  
- `schemes/` — Schematic diagrams in PNG format illustrating electronic components and their connections.  
- `scr/` — Source code for the control software.  
- `t-photos/` — Two photos of the team: an official one and a funny one.  
- `v-photos/` — Six photos of the vehicle from different angles.  
- `video/` — Video file demonstrating the robot driving.

---

## 🚦 Mobility System
Our robot is designed to autonomously evade lateral obstacles, complete three full rotations, and stop at its initial position by using:

- Rear motor (Large Angular Motor) connected to **port B** for forward movement.  
- Front motor (Medium Angular Motor) connected to **port A** for turning.  
- Three ultrasonic sensors connected to **ports D (right), E (left), and F (front)** for detecting obstacles.  
- Integrated gyroscope to track orientation and rotations.

### Key Mobility Features:
- Continuous forward movement with rear motor.  
- Lateral obstacle detection within 10 cm triggers stopping and turning maneuvers (90° left or right).  
- Gyroscope tracks cumulative rotation; after three full rotations (1080°), the robot stops at the initial position.

---

## 🎯 Strategy Summary
- Initialization of hub, motors, and sensors.  
- Continuous forward motion with obstacle monitoring.  
- Obstacle-triggered turning maneuvers using the front motor.  
- Rotation tracking with gyroscope resets after every 360°.  
- Completion after three rotations and stopping.

---

## ⚠️ Challenges and Improvements
One main challenge was refining the robot's turning accuracy. Initially, the robot did not move precisely when turning. As a team, we analyzed and tested solutions, optimizing performance and applying our theoretical knowledge practically, strengthening our teamwork and problem-solving skills.

---

## 🙌 Team Members
- Alexis Quintero — Programming, logic, and testing.  
- Fiorella Campos — Assembly, construction, documentation, GitHub management.  
- Jose Filos — Assembly, construction, project coordination, GitHub support.

---

*Good luck to all teams in WRO 2025!*
