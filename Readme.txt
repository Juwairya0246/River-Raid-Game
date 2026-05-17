# River Raid Game (C++ / OOP)

---

## Overview
A 2D C++ game developed using Object-Oriented Programming principles.

The game simulates a River Raid-style environment with enemy spawning, collision detection, scoring, and fuel management in a real-time gameplay system.

---

## Features
- Enemy spawning system
- Collision detection
- Scoring system
- Fuel management
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

## How to Run

This project uses the **CMUgraphics package**.

### Setup Notes
Documentation for the graphics package is available in `Manual.txt`.

### Key Requirements
- Include `CMUgraphics.h` instead of `graphics.h`
- Ensure proper compiler setup for your IDE
- Some compilers may require modifications in `version.h`

### Important Notes
Some constants were renamed in newer package versions:
- `L_CLICK → LEFT_CLICK`
- `R_CLICK → RIGHT_CLICK`
- `LEFT → LEFT_BUTTON`
- `RIGHT → RIGHT_BUTTON`

Window behavior may require a mouse click to close (`SetWaitClose` in `Manual.txt`).

---

## Demo Files
- `Demo.cpp` → Full graphics package demonstration
- `House.cpp` → Simple example project

---

## 🎯 Purpose
Built as a university project to apply OOP concepts, event-driven programming, and real-time game system design.
