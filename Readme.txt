
# River Raid Game (C++ / OOP)

---

## Project Overview
A 2D C++ game developed using Object-Oriented Programming principles.  
The game simulates a River Raid-style environment with enemy spawning, collision detection, scoring, and fuel management.

---

## Features
- Enemy spawning system  
- Collision detection  
- Scoring system  
- Fuel management system  
- Pause / Resume functionality  
- Save and Load game state  

---

## Concepts Used
- Object-Oriented Programming (OOP)  
- Game Loop Design  
- Event-driven Programming  
- State Management  

---

## Tech Stack
- C++  
- CMU Graphics Library  
- OOP Principles  

---

## How to Run (IMPORTANT)

This project uses the **CMUgraphics package**.

### Setup Notes
Documentation for CMUgraphics is found in `Manual.txt`.

### 🔧 Key Requirements
- Include `CMUgraphics.h` instead of `graphics.h`
- Ensure correct compiler setup for your IDE
- Some compilers may require modifications in `version.h`

### Important Notes
- Some constants were renamed:
  - `L_CLICK → LEFT_CLICK`
  - `R_CLICK → RIGHT_CLICK`
  - `LEFT → LEFT_BUTTON`
  - `RIGHT → RIGHT_BUTTON`

- Window behavior may require mouse click to close (see `SetWaitClose` in Manual.txt)

---

## Demo Files
- `Demo.cpp` → full library demonstration  
- `House.cpp` → simple example project  

---

## Purpose
Built as a university project to apply OOP concepts in a real-time game environment simulation.
