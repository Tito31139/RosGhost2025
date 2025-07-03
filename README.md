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
- Building instructions  

---

## 🚗 Robot Structure and Design
The main design idea was developed by our team using two sources as guidelines: M.V.P and Anton's Mindstorms Hot Rod.

---

## 🔌 Components Assembly and Operating Diagram
- The [`schemes/`](./schemes/) directory contains:  
  - A connection diagram showing all port assignments.  
  - A process diagram detailing the robot's actions.  
  - A list and description of electronic components used.  

---

## 💻 Programming Code
- The [`scr/programacion lego/`](./scr/programacion%20lego/) directory contains the main source code created using LEGO Inventor Mindstorms' block-based system and Python.  
- All programming was done by our team.

---

## 📂 Repository Contents
- [`model/V1/`](./model/V1/) — Files related to robot assembly and parts.  
- [`docs/`](./docs/) — Project plan and competition program documents.  
- [`schemes/`](./schemes/) — Schematic diagrams illustrating electronic components and their connections.  
- [`scr/programacion lego/`](./scr/programacion%20lego/) — Source code for the control software.  
- [`t-photos/`](./t-photos/) — Two photos of the team: an official one and a funny one.  
- [`video/`](./video/) — Video file demonstrating the robot driving.

---

## 🚦 Mobility System
Our robot moves forward continuously using the rear motor (port B).  
It uses three ultrasonic sensors connected to ports D (right), E (left), and F (front) to measure distances to obstacles.  

When the robot detects obstacles on the sides, it chooses to turn toward the side with more free space.  
If there is a lot of free space, it makes turns at corners accordingly.  
The integrated gyroscope counts the number of corners or full turns made.  
After completing three full rotations or corners, the robot stops at its starting position.

---

## 🏃‍♂️ How to Run the Program

1. Turn on the LEGO Mindstorms Large Hub (model 88016) and connect it via Bluetooth or USB to your computer or tablet.  
2. Open the LEGO Mindstorms Inventor app (recommended version 2.0 or higher).  
3. Navigate to the folder [`scr/programacion lego/`](./scr/programacion%20lego/) in this repository and open the main program file.  
4. Upload the program to the Hub.  
5. Place the robot on the competition field or a flat surface.  
6. Start the program from the app or directly on the Hub.  
7. The robot will start moving autonomously, avoiding obstacles and performing the programmed maneuvers.  
8. To stop the robot, use the stop button in the app or turn off the Hub.  

*Make sure all motors and sensors are properly connected to the correct ports as described in the [`schemes/`](./schemes/) folder.*

---

## 🎯 Strategy Summary
- Initialization of hub, motors, and sensors.  
- Continuous forward motion with obstacle monitoring.  
- Turning toward the side with more free space when obstacles are detected.  
- Rotation tracking with the gyroscope counting corners or full turns.  
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
