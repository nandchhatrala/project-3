# Pac-Man Clone using OpenGL

### Author: Patricia Terol  
### Course: CSE 2050  
### Project: assign10

---

## 🎮 Project Overview

This project is a simple Pac-Man-style game developed using **OpenGL** and **GLUT**. It features:

- A maze with border walls and multiple obstacle sections
- A player-controlled Pac-Man character
- Four autonomous monsters with movement
- Dots (food) scattered throughout the map to collect
- A scoring system

---

## 🧱 Structure

- `main.cpp` – Core logic and rendering code
- Maze is defined using:
  - `border`, `obstaclesTop`, `obstaclesMiddle`, `obstaclesBottom`
- Food coordinates are stored in a `deque`
- Game world is represented using a `bitmap` for collision detection

---

## 🎮 Controls

| Key       | Action              |
|-----------|---------------------|
| Arrow Keys | Move Pac-Man        |
| R         | Restart Game        |
| ESC       | Exit Game           |

---

## 🧠 Game Logic

- Food is eaten when Pac-Man overlaps its coordinates
- Monsters move in preset directions
- Collision with monsters ends the game (not shown here but assumed in full project)
- The game ends when all food is eaten

---

## 💻 Requirements

- C++ Compiler
- GLUT and OpenGL libraries installed
- Windows OS (uses `windows.h`)

---

## 🔧 How to Build and Run

1. Install [FreeGLUT](http://freeglut.sourceforge.net/) or use any OpenGL development setup.
2. Compile the project using any C++ compiler that supports OpenGL:
    ```bash
    g++ main.cpp -o PacMan -lopengl32 -lglu32 -lfreeglut
    ```
3. Run the executable:
    ```bash
    ./PacMan
    ```

> Make sure the OpenGL and GLUT libraries are linked properly!

---

## 📌 Notes

- This version of the game is a prototype and does not contain full gameplay features like lives, score display on screen, or full monster AI.
- The code is meant for educational purposes and can be expanded upon for more features.

---

## 📷 Screenshots (optional)

_Add screenshots of gameplay here for better visualization._

---

## 📜 License

MIT License (or as specified by your instructor)
