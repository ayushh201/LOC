# J&K Military Software Project

This project implements a military software system for managing various operations in Jammu and Kashmir (J&K). The software provides functionalities for both war conditions and daily drills, utilizing graph algorithms, data structures, and optimization techniques.

## Features

### War Conditions
1. View map relations of J&K districts
2. View area-wise fatalities
3. Calculate minimum troops required for coverage
4. Find escape paths
5. Optimize supplies storage
6. Calculate all-pairs shortest paths

### Daily Drills
1. View map relations of J&K districts
2. Search for a specific district
3. Classify terror groups
4. Calculate minimum cost of weapons
5. Find shortest path from a single source

## Algorithms and Data Structures Used

- Graph representation using Adjacency List
- Binary Search
- Radix Sort
- Dynamic Programming (for weapon cost calculation)
- Dijkstra's Algorithm (for single-source shortest path)
- Floyd-Warshall Algorithm (for all-pairs shortest paths)
- Welsh-Powell Algorithm (for graph coloring / troop allocation)
- Fractional Knapsack Algorithm (for supplies optimization)

## How to Use

1. Compile and run the C++ program.
2. Choose between "War Conditions" (1) or "Daily Drills" (2).
3. Select specific operations from the menu provided.
4. Follow on-screen instructions for each operation.

## Code Structure

The code is organized into several functions, each implementing a specific algorithm or functionality. Key components include:

- Graph class for representing district connections
- Various sorting and searching algorithms
- Path finding and optimization functions
- Data structures for storing district information and casualties

## Dependencies

- C++ Standard Library
- No external libraries required

## Note

This software is designed for educational and demonstrative purposes. The data and scenarios used are simulated and should not be considered as real-world representations.
