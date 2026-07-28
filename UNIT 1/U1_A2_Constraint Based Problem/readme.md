# Constraint-Based Problem Solving - AI Search Algorithms

## Metadata

- **Title:** Constraint-Based Problem Solving
- **Objective:** To solve real-world constraint satisfaction and search problems using Artificial Intelligence algorithms.
- **Software Used:** Python 3.13
- **Tools:** VS Code
- **Algorithms Implemented:** Backtracking Search, Breadth-First Search (BFS), Uniform Cost Search (UCS), Rule-Based Classification, Brute Force Convex Hull
- **Result:** Successfully implemented constraint-based scheduling, robot path planning, rescue robot navigation, fraud detection, and convex hull computation.

---

## Overview

This repository contains implementations of **Constraint-Based Problem Solving** techniques in Artificial Intelligence (Course Code: CSA17). The assessment focuses on solving real-world problems involving constraints, pathfinding, intelligent agents, optimization, and computational geometry using AI search algorithms.

---

## Structure & Modules Included

### 1. Hospital Doctor Scheduling (Backtracking Search)

#### Problem Statement

Assign three doctors (D1, D2, D3) to Morning, Afternoon, and Night shifts while satisfying scheduling constraints.

#### Constraints

- D1 cannot work the Night shift.
- D2 must work before D3.
- Only one doctor per shift.
- D3 cannot work the Morning shift.
- Every doctor must be assigned exactly one shift.

#### Search Strategy

Uses the **Backtracking Search Algorithm** to systematically explore possible assignments and generate a valid schedule while satisfying all constraints.

---

### 2. Robot Grid Navigation (Breadth-First Search)

#### Problem Statement

Navigate a robot from the Start position (S) to the Goal position (G) in a 5 × 5 grid containing obstacles.

#### Constraints

- Movement allowed in four directions.
- Each movement cost is 1.
- Obstacles cannot be crossed.
- Shortest path must be determined.

#### Search Strategy

Implements **Breadth-First Search (BFS)** to explore the grid level by level and determine the shortest path.

---

### 3. Autonomous Rescue Robot (Uniform Cost Search)

#### Problem Statement

A rescue robot must safely reach a survivor in a disaster-affected building while minimizing total travel cost.

#### Features

- Partial observability
- Dynamic environment
- Risk zones with additional traversal cost
- Obstacle avoidance
- Online decision making

#### Search Strategy

Implements **Uniform Cost Search (UCS)** using a priority queue to guarantee the minimum-cost path.

---

### 4. Fraud Detection in Financial Systems

#### Problem Statement

Analyze financial transactions and classify them as **Fraudulent** or **Legitimate** using predefined constraint rules.

#### Parameters

- Transaction amount
- Transaction location
- Daily transaction frequency

#### Solution Approach

Uses a **Rule-Based Classification System** to detect suspicious financial transactions.

---

### 5. Convex Hull using Brute Force Algorithm

#### Problem Statement

Determine the boundary enclosing a set of two-dimensional points representing obstacle coordinates.

#### Solution Approach

Implements the **Brute Force Convex Hull Algorithm** by checking every pair of points to identify convex hull edges.

---

## Getting Started

### Prerequisites

- Python 3.13 or later
- VS Code (Recommended)

### Execution

Run the consolidated Python program:

```bash
python Python_code.py
```

The program displays the following menu:

```text
1. Hospital Doctor Scheduling
2. Robot Grid Navigation (BFS)
3. Autonomous Rescue Robot (UCS)
4. Fraud Detection System
5. Convex Hull using Brute Force
6. Exit
```

Select any option (1–5) to execute the corresponding module.

---

## Algorithms Used

- Backtracking Search
- Breadth-First Search (BFS)
- Uniform Cost Search (UCS)
- Rule-Based Classification
- Brute Force Convex Hull Algorithm

---

## Software Requirements

| Software | Version |
|----------|---------|
| Python | 3.13 |
| VS Code | Latest Version |

---

## Results

✔ Successfully implemented Hospital Doctor Scheduling using Backtracking Search.

✔ Successfully implemented Robot Grid Navigation using Breadth-First Search (BFS).

✔ Successfully implemented Autonomous Rescue Robot Navigation using Uniform Cost Search (UCS).

✔ Successfully developed a Rule-Based Fraud Detection System.

✔ Successfully implemented the Brute Force Convex Hull Algorithm.

---

## Author

**Artificial Intelligence Laboratory**

**Course Code:** CSA17

---

## License

This project is created for educational and academic purposes.
