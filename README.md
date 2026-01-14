# Drone Dominion (UE5)

A third-person **drone combat prototype** built in **Unreal Engine 5** using **Blueprints**.
This project implements custom flight mechanics, camera systems, and gameplay logic from scratch, developed as a personal implementation of the design concepts from Stephen Ulibarri's Ultimate Developer Course.

## About The Project

This project demonstrates a physics-based drone controller and gameplay loop. While the **visual assets** and **gameplay concept** are based on the [Udemy UE5 Ultimate BP Course](https://www.udemy.com/course/ue5-ultimate-bp-course/), the **Blueprints and core logic were created entirely by me** without relying on the tutorial's step-by-step code.
The goal was to test my understanding of vector math, actor manipulation, and UE5's physics system by reverse-engineering the intended gameplay mechanics.

## Gameplay Demo Video

<video src="https://github.com/user-attachments/assets/bd188f2e-caf1-46ff-b72b-aab8b44021be" controls></video>

### Key Features
* **Custom Drone Physics**: Implemented a physics-based movement system (Thrust, Pitch, Yaw, Roll) from scratch.
* **Dynamic Camera**: Smooth camera follow with lag and stabilization logic.
* **Gameplay Loop**: [You play as a drone, first you spawn and move towards the center chamber where the boss resides, major objective is to destroy the boss].
* **Collision & Interaction**: Custom collision handling and interactive elements.

## 🛠️ Technical Implementation

**Engine**: Unreal Engine 5.6  
**Language**: Blueprints (Visual Scripting)

### "Logic First" Approach
Instead of copying the tutorial nodes, I focused on solving the mechanics independently:
* **Movement**: Calculated forces and torques manually to drive the drone's Static Mesh Component.
* **Input Handling**: Used the Enhanced Input System to map diverse controller/keyboard inputs to flight axes.
* **Optimization**: Logic is structured for readability and performance, utilizing events or interfaces where appropriate.

## Controls
- **W / A / S / D** – Move the drone forward, left, backward, and right  
- **Space** – Apply upward thrust (ascend)
- **Mouse Movement** – Rotate / aim the drone
- **Left Mouse Button** – Fire primary weapon
- **Esc** – Pause menu

## Credits & Acknowledgments
* **Game Design & Assets**: Provided by [Stephen Ulibarri](https://www.udemy.com/user/stephen-ulibarri/) via the *Unreal Engine 5 Blueprints - The Ultimate Developer Course*.
* **Logic & Implementation**: Developed by **[Randhir Prakash]**.


