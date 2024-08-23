# Project Based Learning Workshop 2024 - Autonomous Robot

This repository contains the code and resources for the Project Based Learning (PBL) competition held in 2024. The task was to design and build an autonomous robot using an Arduino Mega board, an ultrasonic sensor, a Pixy camera, and a gyro sensor.

## Project Overview

The main objective of the competition was to create a robot capable of locating, aligning with, and picking up a cube autonomously. The project was divided into the following key functionalities:

1. **Searching**: The robot scans the environment using the Pixy camera and ultrasonic sensor to detect the cube.
2. **Going to the Cube**: Once the cube is detected, the robot moves towards it.
3. **Aligning with the Cube**: The robot uses feedback from the sensors to ensure it is correctly aligned with the cube before attempting to pick it up.
4. **Picking Up the Cube**: The robot activates its mechanism to grasp and lift the cube.

## Code Structure

The codebase is organized into several functions, each responsible for a specific task:

- **Driver Functions**: These functions handle the low-level operations of the robot, such as sensor reading, motor control, and communication between components.
- **Main Functions**: The main logic is split into four primary functions corresponding to the robot's main tasks: searching, moving to the cube, aligning, and picking up.

## Repository Structure

- **src/**: Contains the source code for the robot.
- **include/**: Header files and function declarations.
- **lib/**: Libraries and external dependencies used in the project.
- **test/**: Test cases and scripts for validating the robot's functionality.

## Contributors

This project was a collaborative effort, with contributions from multiple team members during the PBL workshop.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
