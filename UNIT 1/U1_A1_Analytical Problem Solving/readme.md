# Analytical Problem Solving - AI Search Algorithms

## Metadata

- **Title:** Analytical Problem Solving
- **Objective:** To formulate AI search problems and evaluate problem-solving agents.
- **Software Used:** Python 3.13
- **Tools:** VS Code
- **Algorithms Implemented:** Breadth-First Search (BFS), Uniform Cost Search (UCS), Backtracking Search
- **Result:** Successfully implemented BFS for the Water Jug problem, Backtracking for the 8-Queens problem, and Uniform Cost Search for delivery path optimization.

---

# Overview

This repository contains comprehensive analytical problem-solving implementations for key foundational concepts in Artificial Intelligence (Course Code: **CSA17**). The implementations address classic search problems, intelligent agent configurations (PEAS), pathfinding heuristics, and logic simulation frameworks.

---

# Structure & Modules Included

## 1. The Water Jug Problem

### Formulation
Solves the classic **4-gallon and 3-gallon Water Jug Problem** to isolate exactly **2 gallons** of water in the 4-gallon container.

### Search Strategy
Explores the state-space tree using a **Breadth-First Search (BFS)** tracking algorithm to guarantee the shortest operational path sequence.

---

## 2. Mars Rover PEAS Analysis

### Framework
Formal characterization of a robotic planetary exploration environment.

### Components Covered

#### Percepts
- Visual feeds
- LiDAR distance parameters
- Spectrometer telemetry
- Sensor feedback

#### Environment
- Partially Observable
- Stochastic
- Sequential
- Dynamic
- Continuous
- Single-Agent

#### Actions
- Steering control
- Sample collection using drilling
- Chemical analysis sequencing
- Satellite telemetry transmission

#### Performance Measures
- High-yield unique scientific data generation
- Maximum rover safety and preservation
- Minimal resource consumption

#### Agent Architecture
Justifies a **Utility-Based Hybrid Agent** capable of optimizing multiple scientific objectives while considering battery limitations, thermal constraints, and communication delays.

---

## 3. The 8-Queens Challenge

### Formulation
Places **8 queens** on a standard **8 × 8 chessboard** so that no two queens attack each other through rows, columns, or diagonals.

### Search Strategy
Implements an **Incremental Backtracking Search** algorithm that prunes invalid board configurations early, making the search process efficient.

---

## 4. OLA Cab Problem-Solving Agent

### Formulation
Models an on-demand ride-booking optimization system that determines the most suitable route from a passenger's pickup location to the destination.

### Agent Type
A **Goal-Based Problem-Solving Agent** that performs path optimization over a weighted road network.

### Simulation Flow
- Identifies available cabs
- Matches user preferences (Mini, Micro, Sedan, Prime)
- Minimizes pickup time
- Generates the optimal travel sequence

---

## 5. Delivery Network Path Optimization (Uniform Cost Search)

### Formulation
Solves the minimum-cost routing problem for a logistics transportation network connecting multiple warehouses.

### Search Strategy
Implements **Uniform Cost Search (UCS)** using a **Min-Priority Queue**.

### Optimal Solution
The globally optimal path is:

```text
S → A → C → G
```

**Minimum Cost = 4 Units**

The algorithm avoids local optimum solutions and guarantees the least-cost path.

---

# Getting Started

## Prerequisites

- Python **3.13** or later
- VS Code (Recommended)

---

## Execution

Run the consolidated Python program:

```bash
python Python_code.py
```

The program displays the following menu:

```text
1. Water Jug Problem
2. Mars Rover PEAS Analysis
3. 8-Queens Challenge
4. OLA Cab Problem-Solving Agent
5. Delivery Network Path Optimization (UCS)
```

Select any option (**1–5**) to execute the corresponding AI problem-solving module.

---

# Algorithms Used

- Breadth-First Search (BFS)
- Uniform Cost Search (UCS)
- Backtracking Search
- Goal-Based Agent
- Utility-Based Hybrid Agent

---

# Software Requirements

| Software | Version |
|----------|---------|
| Python | 3.13 |
| VS Code | Latest Version |

---

# Results

✔ Successfully implemented the Water Jug Problem using **Breadth-First Search (BFS)**.

✔ Successfully analyzed the **Mars Rover PEAS Framework**.

✔ Successfully solved the **8-Queens Problem** using **Backtracking**.

✔ Successfully simulated the **OLA Cab Goal-Based Agent**.

✔ Successfully implemented **Uniform Cost Search (UCS)** for Delivery Network Path Optimization.

---

# Author

**Artificial Intelligence Laboratory**  
Course Code: **CSA17**

---

## License

This project is created for educational and academic purposes.
