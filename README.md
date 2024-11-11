# Maze-Solving Robot

This project is an autonomous maze-solving robot programmed in HCS12 Assembly Language. The robot navigates a maze by detecting obstacles, making decisions in real-time, and finding its way to the end of the maze using pathfinding algorithms. It was developed to showcase autonomous control and decision-making on an embedded system.

## Features
- **Pathfinding and Error Correction**: Implements pathfinding logic to navigate through a maze and correct its path when it encounters dead ends.
- **Obstacle Detection**: Uses sensors to detect obstacles and adjust its path accordingly.
- **State-Machine Navigation**: Manages the robot's movements (forward, turn, and stop) based on sensor input using a state-machine design.
- **Precise Timing**: Utilizes interrupt handlers to ensure accurate timing, enabling reliable navigation in various lighting and surface conditions.

## Technologies
- **Microcontroller**: HCS12
- **Programming Language**: Assembly Language
- **Sensors**: [Specify types, e.g., IR sensors, ultrasonic sensors, etc., if applicable]

## Setup
1. Connect the sensors and motors to the HCS12 microcontroller as per the circuit diagram.
2. Program the HCS12 with the provided assembly code using an HCS12-compatible IDE or programming tool.

## Usage
1. Place the robot at the starting position of a maze.
2. Power on the robot and allow it to initialize.
3. The robot will autonomously navigate through the maze, adjusting its path based on sensor inputs and returning to the start if a dead end is detected.

## Project Status
This project demonstrates fundamental autonomous navigation and maze-solving techniques. Future improvements may include adding more complex algorithms for faster pathfinding or improving sensor calibration for better accuracy.

