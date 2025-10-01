# Autonomous Delivery Robot Navigation 

Welcome to **Autonomous Delivery Robot Navigation**, a Python-based simulation that demonstrates an autonomous delivery robot navigating a dynamic environment with buildings, obstacles, and delivery tasks. The simulation visualizes every stage of the robot’s journey and tracks comprehensive performance metrics.


---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Environment Setup](#environment-setup)
- [How to Run](#how-to-run)
- [Visualization](#visualization)
- [Metrics & Reporting](#metrics--reporting)
- [Example Use Case](#example-use-case)
- [Dependencies](#dependencies)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## Project Overview

This project simulates an **autonomous delivery robot** that navigates a 2D grid environment with:

- Multiple buildings and obstacles
- Pickup and delivery tasks
- Battery management
- Real-time path replanning when obstacles appear

The robot uses **A\*** pathfinding with Manhattan distance heuristic to navigate efficiently. It continuously updates its metrics and visualizes **every stage** of its journey.

---

## Features

- **Environment Setup**
  - Customizable grid size
  - Buildings with doors
  - Obstacles of any shape/size

- **Delivery Robot**
  - Dynamic path planning with A\* algorithm
  - Battery management with automatic charging
  - Task handling for pickups and deliveries
  - Metrics tracking:
    - Distance traveled
    - Battery consumption
    - Deliveries completed
    - Packages picked
    - Path replans
    - Obstacles avoided
    - Charging sessions
    - Average speed and efficiency

- **Stage-by-Stage Visualization**
  - Full visualization of every simulation step
  - Traveled path vs planned path
  - Real-time delivery progress and task status
  - Battery level and robot status

- **Simulation**
  - Autonomous execution of multiple tasks
  - Automatic handling of low battery
  - Mission completion report with metrics

---

## Environment Setup

1. Clone the repository:
```bash
git clone https://github.com/NawneetRaj/Autonomous_Delivery_Robot_Navigation.git
cd Autonomous_Delivery_Robot_Navigation

The simulation performs:

Initial setup visualization

Step-by-step navigation to pickup and delivery locations

Real-time battery monitoring and charging

Display of path replanning when obstacles block the path

Final mission completion report

Observe interactive plots showing:

Environment layout

Robot path and deliveries

Metrics, progress, and status panels

Visualization
The simulation includes a Stage-by-Stage Visualization:

Map View: Shows robot, buildings, obstacles, pickup/delivery points, and paths.

Metrics Panel: Live updates for distance, battery, deliveries, and efficiency.

Progress Bar: Percentage of completed tasks.

Status Panel: Current position, carrying status, and step count.

Path Analysis: Travel efficiency and replans.

Task Info: Current task details with status.


License
This project is open-source and released under the MIT License.

Author
Nawneet Raj
GitHub Profile

🚀 Build smarter delivery robots and visualize autonomous navigation with metrics in real-time!

