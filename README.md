# Racing Moto - Bike Racing Game

## Overview
Racing Moto is a classic bike racing game developed using Turbo C++ with BGI graphics. The player controls a bike moving through three lanes, avoiding obstacles while collecting bonuses to increase their score.

## Game Features
- Three-lane bike racing gameplay
- Multiple obstacle types (pit holes, humans, bonuses)
- Progressive difficulty with increasing speed
- High score system with persistent storage
- Keyboard-controlled movement (arrow keys)
- Multiple game screens (menu, instructions, high scores)

## How to Play
1. Use LEFT and RIGHT arrow keys to switch lanes
2. Avoid pit holes and humans
3. Collect bonuses (B) for extra points
4. Survive as long as possible to advance levels

## Obstacle Types
- *Bonus (B)*: Collect for +100 points
- *Pit Hole*: Instant game over if hit
- *Human*: Instant game over if hit
- *Pit+Human Combo*: Most dangerous obstacle

## Technical Details
- Developed in Turbo C++
- Uses BGI graphics library
- Saves high scores to "High_Score.txt"
- Requires proper BGI driver path configuration

## File Structure
- Main game logic in single C++ file
- High scores stored in external text file
- Uses standard Turbo C++ libraries (graphics.h, conio.h, etc.)

## Compilation Instructions
1. Open in Turbo C++ IDE
2. Ensure BGI path is correctly set
3. Compile and run

## Controls
- LEFT ARROW: Move bike left
- RIGHT ARROW: Move bike right
- ENTER: Select menu options

## Game Screens
1. Animated intro screen
2. Main menu (Play, Instructions, High Scores, Exit)
3. Gameplay screen
4. Game over screen with stats
5. High score display
6. Exit confirmation

## Note
This game was designed for the classic Turbo C++ environment and may require adjustments to run on modern systems.
