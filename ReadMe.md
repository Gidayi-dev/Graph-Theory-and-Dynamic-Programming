# Graph Theory and Dynamic Programming

This repository serves as an in-depth exploration of **Graph Theory** and **Dynamic Programming**, covering theoretical concepts, algorithmic strategies, and their practical applications. It is designed for learners, developers, and professionals seeking a deeper understanding of these topics.

---

## Graph Theory

Graph theory is a mathematical study of graphs, which consist of nodes (vertices) connected by edges. It provides the foundation for modeling relationships, networks, and pathways in various domains, including computer science, biology, and social sciences.

### Basic Terminology
- **Graph**: A collection of vertices and edges.
- **Vertex (Node)**: A fundamental unit in a graph.
- **Edge**: A connection between two vertices.
- **Directed Graph (Digraph)**: Edges have a direction, connecting one vertex to another.
- **Undirected Graph**: Edges have no direction, allowing bidirectional traversal.
- **Weighted Graph**: Edges have weights or costs associated with them.
- **Cycle**: A path that begins and ends at the same vertex without retracing any edge.
- **Connected Graph**: A graph where there is a path between every pair of vertices.
- **Degree**: The number of edges connected to a vertex.

### Graph Representations
- **Adjacency Matrix**: A 2D matrix where rows and columns represent vertices, and entries indicate the presence or absence of edges.
- **Adjacency List**: A collection of lists where each vertex’s list contains its neighbors.
- **Edge List**: A list of edges, each represented by its two endpoints and optionally a weight.

### Core Algorithms
Graph algorithms form the backbone of graph theory, addressing problems such as traversal, connectivity, shortest paths, and spanning trees.

1. **Traversal**:
   - Breadth-First Search (BFS): Explores vertices layer by layer, useful for finding shortest paths in unweighted graphs.
   - Depth-First Search (DFS): Explores as far as possible along a branch before backtracking, useful for cycle detection and connectivity analysis.

2. **Shortest Path**:
   - Dijkstra’s Algorithm: Calculates shortest paths in weighted graphs without negative weights.
   - Bellman-Ford Algorithm: Solves shortest path problems even with negative weights.
   - Floyd-Warshall Algorithm: Finds all-pairs shortest paths.

3. **Minimum Spanning Tree**:
   - Kruskal’s Algorithm: Selects edges in increasing weight to form a tree.
   - Prim’s Algorithm: Builds the spanning tree by expanding from an initial vertex.

4. **Other Topics**:
   - Topological Sorting: Linear ordering of vertices in Directed Acyclic Graphs (DAGs).
   - Strongly Connected Components (SCCs): Identifying subsets of vertices where every vertex is reachable from any other.

### Advanced Topics
- **Planarity**: Studying graphs that can be drawn on a plane without edges crossing.
- **Graph Coloring**: Assigning colors to vertices so adjacent vertices have different colors.
- **Bipartite Graphs**: Graphs whose vertices can be divided into two disjoint sets such that no two vertices within the same set are adjacent.

---

## Dynamic Programming

Dynamic Programming (DP) is a method for solving problems by breaking them into overlapping subproblems and solving each only once. It is widely used in optimization and combinatorial problems.

### Key Concepts
- **Overlapping Subproblems**: Problems where solutions to subproblems are reused multiple times.
- **Optimal Substructure**: The solution to a problem can be constructed from the solutions of its subproblems.

### Approaches
1. **Memoization**:
   - A top-down approach that involves recursive computations and caching results of solved subproblems.

2. **Tabulation**:
   - A bottom-up approach that builds solutions iteratively using a table to store results.

### Problem Categories
Dynamic Programming problems can be broadly classified based on their structure and objectives:

1. **Optimization Problems**:
   - Knapsack Problem: Selecting items to maximize value while staying within weight capacity.
   - Matrix Chain Multiplication: Finding the most efficient way to multiply matrices.

2. **Sequence Problems**:
   - Longest Common Subsequence (LCS): Determining the longest sequence shared by two strings.
   - Longest Increasing Subsequence (LIS): Finding the longest subsequence where elements increase consecutively.

3. **Counting Problems**:
   - Coin Change Problem: Calculating the number of ways to make a given amount using different denominations.
   - Staircase Problem: Counting distinct ways to climb a staircase with variable step sizes.

### Advanced Techniques
- **Bitmask DP**: A compact way to represent states in subset-based problems.
- **Tree DP**: Solving problems defined on tree structures.
- **DP on Graphs**: Combining graph traversal with DP to solve path-related problems like the Traveling Salesman Problem.

---

## Applications

### Graph Theory Applications
- **Network Design**: Optimizing connectivity in communication networks.
- **Social Network Analysis**: Studying relationships and influence among individuals.
- **Routing and Navigation**: Finding shortest paths in transportation and logistics.

### Dynamic Programming Applications
- **Bioinformatics**: Sequence alignment and protein folding.
- **Game Development**: Calculating optimal strategies in games.
- **Resource Allocation**: Optimizing use of limited resources in business processes.

These notes provide a foundation for further exploration of these powerful computational tools and their wide-ranging applications.
