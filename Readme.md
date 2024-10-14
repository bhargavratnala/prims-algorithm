# Prim's Algorithm Visualization

This project demonstrates **Prim's Algorithm** for finding the **Minimum Spanning Tree (MST)** of a graph. The visualization is implemented using **HTML divs** to represent nodes and **SVG** to draw edges between them. The algorithm is animated step-by-step to show how it progressively selects the minimum edge at each step.

## Features
- **Visual Graph Representation**: Nodes are displayed as interactive `div` elements, and edges are drawn using **SVG lines**.
- **Prim's Algorithm Animation**: Shows each step of Prim's algorithm as it selects edges to form the MST.
- **Dynamic Edge Weights**: Edges have different weights, and the algorithm selects the minimum weighted edges.
- **Interactive Interface**: Users can see the process of selecting nodes and edges in real time.

## Demo
You can view a live demo of the project [here](#).

## Technologies Used
- **HTML**: For creating node elements using `div`s.
- **CSS**: For styling nodes and the graph layout.
- **JavaScript**: For implementing Prim's algorithm logic and managing interactivity.
- **SVG**: For drawing edges between the nodes dynamically.

## Installation and Setup

### Prerequisites
A modern browser that supports **SVG** and **JavaScript**.

### Steps to Run Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/prims-algorithm-visualization.git
    ```

2. Navigate to the project directory:
    ```bash
    cd prims-algorithm-visualization
    ```

3. Open the `index.html` file in your preferred browser to start the visualization.

### Running on a Local Server
If you'd like to run it on a local server (e.g., for development purposes), you can use **Live Server** or any other local server tool.

1. Install Live Server globally:
    ```bash
    npm install -g live-server
    ```

2. Run Live Server in the project folder:
    ```bash
    live-server
    ```

3. Open your browser and visit:
    ```
    http://localhost:8080
    ```