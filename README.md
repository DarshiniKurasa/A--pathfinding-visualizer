# A* Pathfinding Visualizer

This project is an interactive visualizer for the A* pathfinding algorithm, developed using Python and the Pygame library. It provides a hands-on way to observe the A* algorithm in action, demonstrating how it navigates around obstacles to find the shortest path between two points.

## Features

- **Interactive Grid Creation**: Click on the grid to set a start point, end point, and barriers.
- **Real-Time Visualization**: Watch the algorithm's progress as it explores the grid, adding nodes and finding the optimal path.
- **Reset Functionality**: Clear the grid and reset the start and end points with a single key press.

## How It Works

1. **Start Point**: Left-click on a cell to set the start point (orange).
2. **End Point**: Left-click on another cell to set the end point (turquoise).
3. **Barriers**: Left-click on additional cells to create barriers (black), which the algorithm will navigate around.
4. **Run A\* Algorithm**: Press the `Space` key to start the pathfinding visualization.
5. **Reset Grid**: Press the `C` key to clear the grid and start fresh.

## Requirements

- Python 3.x
- Pygame library (`pip install pygame`)
![image](https://github.com/user-attachments/assets/9721ca0f-9f38-4dea-b980-29a9718d6f2c)


## Usage
Run the script to launch the visualizer.
## python pathfinding_visualizer.py
Use left-click to set the start, end, and barrier points as described above.
Press Space to begin the visualization, and C to clear the grid.

## Explanation of the A* Algorithm
The A* algorithm is an efficient pathfinding algorithm that uses a heuristic to estimate the shortest path from a start to an end node. In this project:

The g_score represents the exact cost to reach each node from the start.
The f_score is the sum of the g_score and the heuristic distance to the end node (calculated using the Manhattan distance).
Nodes are evaluated by their f_score values, allowing the algorithm to prioritize promising paths.
Controls
Left Click: Place the start, end, or barrier points.
Right Click: Remove barriers or reset start/end points.
Space: Run the A* algorithm.
C: Clear the grid.

## Acknowledgments
Built using the Pygame library.
Inspired by the concept of visualizing pathfinding algorithms to make learning more interactive.

This README will give users all the essential details needed to understand, run, and modify 
