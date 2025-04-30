# Smart Traffic Management System Simulation

A real-time smart traffic management system simulation developed using Python, Tkinter, raw sockets, and sensor-based logic. This project demonstrates how intelligent traffic systems can optimize urban traffic flow with support for emergency vehicle prioritization.

## Overview

This project simulates a single-lane road where vehicles respond dynamically to traffic signals. The system:
- Uses simulated sensor inputs to detect vehicle density.
- Implements raw socket communication to mimic real-time data exchange between sensors and the control system.
- Automatically prioritizes ambulances by turning the signal green when detected.
- Displays a visual interface using Tkinter to clearly simulate signal behavior and vehicle movement.

## Features

- Real-time vehicle movement with accurate stop/go logic
- Dynamic signal control based on vehicle density and emergency presence
- Ambulance detection and signal override
- Raw socket-based communication for simulating sensor-network interaction
- Graphical interface using Tkinter for simulation visualization

## Technologies Used

- Python
- Tkinter (for GUI)
- Socket Programming (raw sockets)
- Object-oriented programming
- Basic traffic flow logic and simulation

## How to Run

1. Clone the repository.
2. Ensure Python 3.x is installed.
3. Run the simulation script:
   ```bash
   python traffic_simulation.py
