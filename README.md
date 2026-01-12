# Nearest Neighbour Lab (C++)

A C++ implementation of the **Nearest Neighbour algorithm**, developed as a lab project to explore basic Machine Learning, distance calculations, and performance-oriented problem solving using a low-level, strongly typed language.

This project focuses on algorithm correctness, efficiency, and clean separation of logic rather than UI or external frameworks.

---

## 📌 Project Overview

The **Nearest Neighbour algorithm** is an approach that essentially creates a 3D graph with multiple points (X, Y, Z) using a test file with information to fill this graph, is tested with a file with correct labels, and the contains a file with data but no labels to attempt to correctly label that data and output a file with the determined labels

- Basic Nearest Neighbour Algorithm

This lab implements the algorithm entirely in **C++**, emphasizing manual control over data structures and execution flow.

---

## 🎯 Objectives

- Implement a nearest neighbour solution from scratch
- Practice algorithm design using C++
- Apply distance metrics to real data
- Reinforce efficient iteration and state tracking
- Strengthen debugging and testing skills in a compiled language

---

## 🧠 Algorithm Breakdown

1. Select a starting point
2. Compute distances from the current point to all unvisited points
3. Choose the closest point
4. Mark it as visited and move to it
5. Repeat until all points are processed
6. Outputs a file with the determined labels

This approach is fast and easy to reason about, though it does **not guarantee a globally optimal solution**.

---

## 🛠️ Tech Stack

- **Language:** C++
- **Standard:** C++11 or newer
- **Paradigm:** Procedural / Object-Oriented
- **Execution:** Command-line application

No third-party libraries are required.

---

## ▶️ How to Build & Run

### Prerequisites
- C++ compiler (`g++`, `clang++`, or MSVC)

### Build (Linux / macOS)

```bash
g++ -std=c++11 -o nearest_neighbor main.cpp
```

### Run
```bash
./nearest_neighbor
```
