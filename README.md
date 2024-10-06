# Retro Snake Game in C++ with Raylib

## Overview
This project is a retro Snake game built using C++ and the Raylib library. The main goal of this project was to practice Object-Oriented Programming (OOP) concepts in C++, keeping the entire game logic in a single file for simplicity. 

The game implements core OOP principles such as encapsulation, abstraction, and reusability, wrapped in a fun, interactive game. The snake can be controlled by either arrow keys or specific alternative keys (IJKL).

[Watch the Demo Video on YouTube](https://www.youtube.com/watch?v=WWwxZBHeyjk)

## Features
- Classic Snake gameplay.
- Snake movement is controlled using both arrow keys and alternative keys (IJKL).
- Simple collision detection with edges and tail.
- Food spawning with random placement avoiding snake body positions.
- Sound effects for eating food and hitting walls.
- Object-Oriented structure with classes for `Snake`, `Food`, and `Game`.

## Gameplay
- **Move**: Use Arrow keys or alternative keys (IJKL) to control the direction of the snake.
- **Objective**: Eat the food and grow the snake without hitting the edges or its tail.
- **Score**: Increases every time the snake eats food.

## OOP Concepts Implemented
- **Snake**: A class that manages the snake's body and movement.
- **Food**: A class that manages the generation of food on the game grid.
- **Game**: A class that contains the game loop, handles user inputs, and detects collisions.

## Dependencies
- [Raylib](https://www.raylib.com/) (for window, input handling, and graphics)
- C++17 or later

## How to Build & Run
