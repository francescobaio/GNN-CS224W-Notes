
This glossary provides definitions for key terms referenced in these lecture notes on Graph Neural Networks. Each entry is organized alphabetically for quick reference.

## A

- **Adjacency List:**  
  A data structure used to represent a graph, where each node is associated with a list of its neighboring nodes. This is particularly efficient for sparse graphs.

- **Adjacency Matrix:**  
  A square matrix used to represent a graph. Each element at row *i* and column *j* indicates the presence (and possibly the weight) of an edge between nodes *i* and *j*. In sparse graphs, most entries are zero.

## B

- **Bipartite Graph:**  
  A graph whose vertices can be divided into two disjoint sets such that every edge connects a vertex from one set to a vertex from the other set. There are no edges connecting vertices within the same set.

## C

- **Connectivity:**  
  A property of a graph that determines whether there is a path between every pair of nodes. A graph is connected if every node can be reached from every other node.

- **Connected Component:**  
  A subgraph in which any two vertices are connected by paths, and which is not connected to any additional vertices in the overall graph.

## D

- **Directed Graph (Digraph):**  
  A graph in which edges have a direction, indicating a one-way relationship between nodes.

- **Degree (Node Degree):**  
  The number of edges incident to a node. In directed graphs, this can be divided into in-degree (number of incoming edges) and out-degree (number of outgoing edges).

## G

- **Graph:**  
  A mathematical structure composed of a set of nodes (vertices) and a set of edges that connect pairs of nodes. Graphs are used to model relationships between entities.

- **Graph Representations:**  
  Methods for encoding a graph into a data structure that can be processed by algorithms, such as using an adjacency matrix or an adjacency list.

## M

- **Manual Feature Engineering:**  
  The process of manually selecting or designing features from raw data for use in machine learning models. In Graph ML, representation learning often reduces the need for extensive manual feature engineering.

- **Multigraph:**  
  A graph that allows multiple edges (parallel edges) between the same pair of nodes.

## N

- **Node:**  
  The fundamental unit or vertex in a graph, representing an individual entity.

- **Node Embedding:**  
  A learned vector representation of a node in a d-dimensional space that captures the node’s properties and its structural position within the graph.

## R

- **Representation Learning:**  
  The process by which a model automatically learns to represent data (such as nodes in a graph) in a way that is useful for downstream tasks, minimizing the need for manual feature engineering.

## S

- **Spatial Graph:**  
  A graph in which nodes have a physical or geometric interpretation, such as representing amino acids in a protein where edges are defined based on spatial proximity.

- **Strong Connectivity:**  
  In a directed graph, the condition where for every pair of nodes (u, v), there exists a directed path from u to v and from v to u.

- **Strongly Connected Components:**  
  Maximal subgraphs of a directed graph in which every node is reachable from every other node via directed paths.

- **Weak Connectivity:**  
  In a directed graph, the graph is weakly connected if replacing all directed edges with undirected edges results in a connected graph.
