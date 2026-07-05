Opinion Simulation of Social Networks

Project Overview

This project simulates how opinions spread through social networks under the influence of a persistent bot agent. The simulation uses a Barabasi-Albert network model to create a realistic social network structure and implements opinion dynamics based on the DeGroot model.

The project investigates how different centrality measures (degree, betweenness, and closeness) affect the speed and pattern of opinion convergence when combined with bot influence.

Features

- Realistic Network Generation: Creates scale-free social networks using the Barabasi-Albert model
- Directional Influence Modelling: Assigns random influence weights to connections, normalised to sum to 1
- Centrality Analysis: Computes degree, betweenness, and closeness centrality
- Bot Influence Simulation: Models a persistent bot with a fixed opinion
- Strategy Comparison: Tests three strategies for amplifying bot influence
- Comprehensive Visualisation: Includes network graphs, convergence plots, heatmaps, and animations

Technologies Used

- Python 3.x - Primary programming language
- NetworkX - Network generation and analysis
- NumPy - Numerical operations and matrix manipulation
- Matplotlib - Static and animated visualisations
- Seaborn - Enhanced visualisations
- Pandas - Data manipulation and analysis
- IPywidgets - Interactive visualisations

Key Findings

1. Degree centrality is the most effective strategy for spreading opinions through the network
2. Betweenness centrality shows moderate effectiveness in spreading opinions
3. Closeness centrality is the least effective strategy among the three tested
4. Degree centrality has the strongest correlation (0.67) with final opinions
5. Bot influence spreads gradually over time, not instantly

Installation, Prerequisites

- Python 3.6 or higher
- Google Colab or Jupyter Notebook environment

Required Libraries

pip install networkx matplotlib seaborn pandas ipywidgets numpy

Running the Simulation

1. Open the notebook in Google Colab or Jupyter Notebook
2. Run all cells in order
3. The simulation will generate the network, compute centrality measures, run opinion dynamics, and display visualisations

Results

Network Visualisations
- Initial social network structure with 50 nodes
- Directional influence network with influence percentages
- Bot and influence classification network

Convergence Analysis
- Comparative convergence under three strategies
- Individual opinion trajectories
- Heatmap of opinion dynamics
- Animated opinion spread

