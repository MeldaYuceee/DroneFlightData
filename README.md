# DroneFlightData – Mini Drone Telemetry Visualization

> **Domain:** UAV Telemetry / Data Visualization  
> **Level:** Beginner (Student R&D)  
> **Purpose:** Visualize basic flight telemetry (altitude, speed, distance) and generate a simple altitude animation from recorded flight data

---

## 1. Background & Concept
Small UAV platforms generate basic telemetry such as altitude, speed and distance. Even with minimal numerical data, meaningful visual insight can be produced through simple plotting and animation.

This project demonstrates how raw flight values can be loaded and visualized using Python, including:
- numerical plotting,
- CSV ingestion,
- and animated altitude playback.

---

## 2. What the Project Provides
- Load flight data from CSV  
- Plot altitude, speed and distance against time  
- Real-time style altitude animation (using `FuncAnimation`)  
- Optionally enter flight values manually  
- Simple usage and lightweight code

---

## 3. Project Structure
DroneFlightData/
├── main.py # Basic plotting
├── main_csv.py # Seaborn version for styling
├── drone_animation.py # Altitude animation
├── flight_data.csv # Sample telemetry
└── README.md
---

## 4. Installation
```bash
pip install matplotlib pandas seaborn

