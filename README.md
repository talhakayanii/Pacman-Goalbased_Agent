# Pacman Game Optimization Using Goal-Based Agent
## Description:

This project simulates a Pacman game using a goal-based agent. The agent moves Pacman through a grid to collect food pellets and power pellets while avoiding ghosts. The game uses Dijkstra’s Algorithm and search strategies to optimize Pacman’s path towards the goal, ensuring that all food and power pellets are collected efficiently. The system also implements utility-based decision-making for Pacman’s movements.

## Features:

Pacman Agent: A goal-based agent that moves Pacman to collect food and power pellets while avoiding obstacles.

Grid Environment: A 4x4 grid environment with food, power pellets, ghosts, and walls. Pacman starts at the top-left corner.

Utility Calculation: Each move has a calculated utility, guiding Pacman to select the best action based on available options.

Game Completion: The game ends once all food and power pellets are consumed, and the score is displayed.

## How it Works:

Grid Initialization: The grid is initialized with different types of cells (e.g., Pacman, food, ghosts, walls).

Movement: Pacman moves across the grid using search algorithms, collecting food and power pellets while considering travel costs and penalties.

Game Progression: The agent’s goal is to collect all food and power pellets while navigating the grid, updating the score after each move.

Optimal Pathfinding: The game optimizes Pacman’s movement using utility calculations for each action taken during the game.
