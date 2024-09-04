# Vishwakarma Mapping System

A C-based application for creating, managing, and analyzing a graph-based map system. It supports adding edges, saving maps to files, printing the graph, finding paths, and computing shortest distances.

## Features

- **Add Edges**: Add connections between nodes with specified distance and direction.
- **Save Map**: Save the map's current state to a file.
- **Print Graph**: Display the map's adjacency list representation.
- **Find Paths**: Compute and display all paths between two nodes.
- **Shortest Path**: Calculate and display the shortest path from a source node to all other nodes using Dijkstra's algorithm.

## Files

- `map_creator.c`: Main program file implementing the map creation, edge addition, and other functionalities.
- `map_loader.c`: (Additional file for loading and managing map data, if applicable)

## Compilation

Compile the program using `gcc`:

```bash
gcc -o map_creator map_creator.c
```
A sample.txt map has been created as an example .
The Screenshots of the project have been uploaded above.
