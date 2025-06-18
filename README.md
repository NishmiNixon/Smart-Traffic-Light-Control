# 🚦 Smart Traffic Light Control using ACO and Fuzzy Logic

This project presents an intelligent traffic control simulation inspired by **Ant Colony Optimization (ACO)** and **Fuzzy Logic**. Vehicles are treated as ants that deposit pheromones based on traffic density, and fuzzy inference rules help determine the optimal road selection dynamically.

## 📌 Project Overview

- **ACO Concept**: Simulates pheromone deposition by vehicles to represent traffic density.
- **Fuzzy System**: Takes `pheromone level` and `distance` as inputs to decide `path preference`.
- **Randomization Impact**: Introduces probabilistic road selection to prevent congestion buildup and simulate real-world unpredictability.
- **Visualization**: Graphs depict pheromone trends using a moving average, showing the effect of optimization over time.

## 🔍 Features

- Adaptive road/path selection based on real-time traffic conditions.
- Two modes:
  - **With randomization**: Probabilistic selection using fuzzy outputs.
  - **Without randomization**: Deterministic selection of highest desirability.
- Fuzzy control system built using `scikit-fuzzy`.
- Matplotlib-based visualizations for comparative analysis.

## 🧠 Tech Stack

- Python
- NumPy
- Matplotlib
- scikit-fuzzy
