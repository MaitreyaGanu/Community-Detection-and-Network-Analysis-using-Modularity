# Community Detection and Network Analysis using Modularity

The project was undertaken as part of my **winter internship at Indian Institute of Science Education and Research , Thiruvananthapuram**.
This project focuses on detecting communities within a network using **modularity optimization**. Modularity is a measure of the strength of division of a network into communities, and this project uses it to identify groups of nodes that are more densely connected internally than to the rest of the network. The analysis is carried out using various network analysis techniques and Python libraries.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)



## Introduction

Community detection is a key task in network analysis and is used to identify groups of nodes within a larger network that have dense connections. These groups, called communities, often represent clusters in real-world networks such as social networks, biological networks, and web graphs.

In this project, the goal is to apply **modularity-based community detection** to a given network. Modularity measures how well the network can be divided into communities based on the edges between them. The project uses a graph-based approach to identify these communities and analyze the network structure.

### What is Modularity?

Modularity is a score that quantifies the quality of a division of a network into communities. A high modularity indicates that there are dense connections within communities and sparse connections between communities. The modularity value ranges from -1 to 1, where a higher value indicates a better division.

## Features

- **Graph Construction**: The network is represented as a graph, where nodes represent entities, and edges represent relationships or interactions between them.
- **Modularity Optimization**: The core algorithm used for community detection is based on optimizing modularity to find the best community structure.
- **Visualization**: The detected communities are visualized using network graphs, where different communities are represented by distinct colors.
- **Performance Evaluation**: The performance of the community detection is evaluated by examining modularity scores and comparing the results with ground truth (if available).
- **Network Metrics**: The project also provides various network metrics such as degree centrality, betweenness centrality, and clustering coefficient to further analyze the network.

## Technologies Used

- **Python**: The main programming language for this project.
- **NetworkX**: A Python library for the creation, manipulation, and study of complex networks.
- **Matplotlib**: For visualizing the network and the communities.
- **Community**: A Python library for community detection based on modularity.
- **NumPy**: For numerical computations.
- **Pandas**: For handling and manipulating network data.
