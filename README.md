# Disaster-Relief-CoppeliaSim-Robot
Disaster Relief CoppeliaSim Simulation Robot

Overview
This project involves designing a disaster recovery environment and creating a disaster relief robot to navigate and search for survivors. The simulation is set in the aftermath of a hurricane, with obstacles such as water leaks and debris.

The simulation demonstrates how a disaster relief robot can navigate a hurricane-damaged environment to locate and assist survivors. The robot uses sensors to detect obstacles and people, providing crucial information for rescue teams.

Features

Obstacle Navigation: The robot navigates around water leaks and debris.
Survivor Detection: The robot detects and locates individuals trapped inside the structure.
Damage Assessment: The robot assesses the damage and provides real-time data to rescue teams.
Environment Description

The disaster recovery environment is designed to mimic the aftermath of a hurricane within an enclosed room similar to an auditorium. Key features include:

Walls and Door: Four cuboid walls and one cuboid door, the only entry and exit point.
Water Leaks: Two water leaks represented by blue cylinders.
Debris: Three large pieces of debris, one blocking the door.
Survivors: Nine individuals represented by colored cuboids.
Robot Modifications

Sensors Added
Proximity Sensors: Three sensors added to the robot to widen its field of view and increase its detection range.
Configuration: The sensors are configured to detect obstacles and survivors, changing color upon detection and providing feedback in the command line.
Justification
The modifications allow the robot to efficiently navigate the environment, detect obstacles and survivors, and provide accurate information for rescue operations. The sensors ensure the robot can operate effectively in the challenging post-hurricane scenario.

Internal Representation

The robot maintains an internal representation of the environment through:

Sensors: Continuously gather data on surroundings and objects.
Detected Objects Table: Stores and tracks detected objects.
Robot Trace Function: Visually traces the robot's path within the simulation environment.

Implementation of Key Concepts
Reasoning
The robot uses reasoning to navigate around obstacles based on sensor inputs, making decisions to avoid collisions and explore new paths.
Knowledge Representation
Detected objects are stored in a table, and the robot traces its path to avoid revisiting areas. Sensor data is visualized to help analyze distances and movements.
Uncertainty
The robot adjusts its behavior based on sensor inputs, managing uncertainty by making real-time decisions to optimize its path and avoid obstacles.
Intelligence
The robot's intelligence is demonstrated through its goal-oriented behavior, learning from interactions with the environment, and adapting its pathfinding strategies.

Installation Guide
Open CoppeliaSim and load the project file.
Ensure the robot's sensors are correctly configured.
Run the simulation to see the robot navigate the environment and locate survivors.
