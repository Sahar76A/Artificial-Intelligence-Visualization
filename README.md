# Artificial-Intelligence-Visualization

A Python-based visualization system for demonstrating how classical Artificial Intelligence search algorithms operate step-by-step on graph structures.

This project provides animated visual representations of popular informed and uninformed search algorithms using the Manim animation engine, helping students and developers better understand algorithm traversal behavior, pathfinding, and heuristic-based decision making.

---

## Features

- Visual animation of graph traversal algorithms
- Step-by-step exploration rendering
- Educational visualization of search behavior
- Support for both informed and uninformed search methods
- Cost and heuristic visualization for A* Search
- Configurable graph inputs through text files

---

## Implemented Algorithms

### Uninformed Search
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Iterative Deepening Search (IDS)

### Informed Search
- A* Graph Search

---

## Technologies Used

- Python
- Manim Community Edition
- Graph Theory Concepts
- Artificial Intelligence Search Algorithms

---

## Project Structure

```bash
├── GraphSystem.py          # Graph creation and visualization system
├── UninformedSearch.py     # BFS, DFS, IDS implementations
├── InformedSearch.py       # A* Search implementation
├── GlobalFunctions.py      # Shared utility functions
├── input.txt               # Sample graph input
├── test.py                 # Testing scripts
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Danial-Kord/Artificial-Intelligence-Visualization.git
cd Artificial-Intelligence-Visualization
```

Install dependencies:

```bash
pip install manim
```

---

## Running the Project

Run a visualization using:

```bash
python test.py
```

Or render animations directly with Manim:

```bash
manim filename.py SceneName
```

---

## Example Concepts Demonstrated

- Queue-based traversal in BFS
- Stack-based traversal in DFS
- Depth-limited exploration in IDS
- Heuristic evaluation in A* Search
- Path cost calculation and node expansion

---

## Educational Purpose

This project was developed as an educational tool to simplify understanding of AI search algorithms through visual learning techniques. It is especially useful for:

- Artificial Intelligence courses
- Data Structures and Algorithms courses
- Graph Theory learning
- Algorithm visualization demonstrations

---

## Future Improvements

- Uniform Cost Search (UCS)
- Greedy Best-First Search
- Dijkstra’s Algorithm
- Interactive GUI
- Weighted graph customization
- Real-time user graph input

