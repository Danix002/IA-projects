# Maze Navigation & State-Space Exploration

This module implements a logic-based pathfinding agent within a grid-based environment, leveraging **Prolog** for reasoning and **Python** for the interface and control logic.

### Prerequisites & Installation

To ensure the system functions correctly, **SWI-Prolog** must be installed and configured in your system's PATH. Once the logic engine is set up, install the necessary Python dependencies—primarily the `pyswip` library, which facilitates the bridge between Python and the Prolog interpreter:

```bash
pip install -r requirements.txt
```

### Experimental Setup and Benchmarking

To rigorously evaluate the efficiency of the state-space search algorithms, we designed and implemented **multiple environment configurations**. These scenarios vary in complexity, obstacle density, and resource distribution, allowing for a comprehensive assessment of the agent's performance across different search spaces.

The following aspects were prioritized during testing:
* **Algorithmic Optimality:** Evaluating the shortest path discovery in various maze topologies.
* **Resource Heuristics:** Testing the agent's ability to prioritize hammers and gems effectively.
* **Search Space Scalability:** Measuring performance as the grid dimensions and constraint density increase.

### Results and Documentation

A detailed analysis of the test cases, including performance metrics, visual representations of the state-space exploration, and a comparative study of the results, is available in the project's formal presentation.

> [!IMPORTANT]
> Please refer to the **`Presentazione IALAB.pptx`** (or the relevant file in the repository) for a complete breakdown of the experimental results, benchmarking data, and architectural diagrams.
