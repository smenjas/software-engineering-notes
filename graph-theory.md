# [Graph Theory](https://en.wikipedia.org/wiki/Graph_theory)

- A graph is a network of connected nodes.
- A connection with a direction is an arc.
- A connection without a direction is an edge.
- A connection can have a weight or cost.
- A graph with directions is called a [directed graph, or digraph](https://en.wikipedia.org/wiki/Directed_graph).
- A graph with weights is called a weighted graph.
- You may want to visit every node: the [travelling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem).
- You may want to find the shortest or cheapest path.

# Representations
You can represent a graph as a list of edges or arcs:
- 1 -> 2
- 2 -> 3
- 2 -> 4
- 3 -> 4
- 3 -> 5
- 3 -> 6
- 4 -> 1
- 4 -> 5
- 5 -> 2

You can represent a graph as a [dictionary](https://en.wikipedia.org/wiki/Associative_array) of [lists](https://en.wikipedia.org/wiki/List_%28abstract_data_type%29), where each key is a node, and each value is a list of connected nodes.
```python3
graph = {1: [2],
         2: [3, 4],
         3: [4, 5, 6],
         4: [1, 5],
         5: [2]}
```

## Definitions
- [Glossary of graph theory terms](https://en.wikipedia.org/wiki/Glossary_of_graph_theory_terms)
- [Clique](https://en.wikipedia.org/wiki/Clique_%28graph_theory%29)
- [Conceptual graph](https://en.wikipedia.org/wiki/Conceptual_graph)
- [Dense graph](https://en.wikipedia.org/wiki/Dense_graph)
- [Directed graph](https://en.wikipedia.org/wiki/Directed_graph)
- [Existential graph](https://en.wikipedia.org/wiki/Existential_graph)
- [Flow network](https://en.wikipedia.org/wiki/Flow_network)
- [Graph (discrete mathematics)](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29)
- [Graph (abstract data type)](https://en.wikipedia.org/wiki/Graph_%28abstract_data_type%29)
- [Graph algebra](https://en.wikipedia.org/wiki/Graph_algebra)
- [Graph coloring](https://en.wikipedia.org/wiki/Graph_coloring)
- [Graph drawing](https://en.wikipedia.org/wiki/Graph_drawing)
- [Graph enumeration](https://en.wikipedia.org/wiki/Graph_enumeration)
- [Graph equation](https://en.wikipedia.org/wiki/Graph_equation)
- [Graph operations](https://en.wikipedia.org/wiki/Graph_operations)
- [Graph rewriting](https://en.wikipedia.org/wiki/Graph_rewriting)
- [Graph traversal (a.k.a. graph search)](https://en.wikipedia.org/wiki/Graph_traversal)
- [Hypergraph](https://en.wikipedia.org/wiki/Hypergraph)
- [Logical graph](https://en.wikipedia.org/wiki/Logical_graph)
- [Loop](https://en.wikipedia.org/wiki/Loop_%28graph_theory%29)
- [Mixed graph](https://en.wikipedia.org/wiki/Mixed_graph)
- [Multigraph](https://en.wikipedia.org/wiki/Multigraph)
- [Neighborhood](https://en.wikipedia.org/wiki/Neighbourhood_%28graph_theory%29)
- [Network theory](https://en.wikipedia.org/wiki/Network_theory)
- [Null graph](https://en.wikipedia.org/wiki/Null_graph)
- [Partially ordered set](https://en.wikipedia.org/wiki/Partially_ordered_set)
- [Path](https://en.wikipedia.org/wiki/Path_%28graph_theory%29)
- [Perfect graph](https://en.wikipedia.org/wiki/Perfect_graph)
- [Principle of compositionality](https://en.wikipedia.org/wiki/Principle_of_compositionality)
- [Quantum graph](https://en.wikipedia.org/wiki/Quantum_graph)
- [Random graph](https://en.wikipedia.org/wiki/Random_graph)
- [Strongly connected component](https://en.wikipedia.org/wiki/Strongly_connected_component)
- [Symmetric graph](https://en.wikipedia.org/wiki/Symmetric_graph)
- [Transitive reduction](https://en.wikipedia.org/wiki/Transitive_reduction)
- [Tree](https://en.wikipedia.org/wiki/Tree_%28graph_theory%29)
- [Vertex](https://en.wikipedia.org/wiki/Vertex_%28graph_theory%29)

## Subareas
- [Algebraic graph theory](https://en.wikipedia.org/wiki/Algebraic_graph_theory)
- [Geometric graph theory](https://en.wikipedia.org/wiki/Geometric_graph_theory)
- [Extremal graph theory](https://en.wikipedia.org/wiki/Extremal_graph_theory)
- [Probabilistic graph theory](https://en.wikipedia.org/wiki/Random_graph)
- [Topological graph theory](https://en.wikipedia.org/wiki/Topological_graph_theory)

## Problems
- [3 utilities](https://en.wikipedia.org/wiki/Three_utilities_problem)
- [7 Bridges of Königsberg](https://en.wikipedia.org/wiki/Seven_Bridges_of_K%C3%B6nigsberg)
- [Art gallery](https://en.wikipedia.org/wiki/Art_gallery_problem)
- [Covering problems](https://en.wikipedia.org/wiki/Covering_problems)
  - [Dominating set](https://en.wikipedia.org/wiki/Dominating_set)
  - [Edge cover](https://en.wikipedia.org/wiki/Edge_cover)
  - [Set cover problem](https://en.wikipedia.org/wiki/Set_cover_problem)
  - [Vertex cover](https://en.wikipedia.org/wiki/Vertex_cover)
- [Graph sandwich](https://en.wikipedia.org/wiki/Graph_sandwich_problem)
- [Hamiltonian path](https://en.wikipedia.org/wiki/Hamiltonian_path_problem)
- [Minimum spanning tree](https://en.wikipedia.org/wiki/Minimum_spanning_tree)
- [Route inspection](https://en.wikipedia.org/wiki/Route_inspection_problem)
- [Steiner tree](https://en.wikipedia.org/wiki/Steiner_tree_problem)
- [Shortest path](https://en.wikipedia.org/wiki/Shortest_path_problem)
- [Subgraph isomorphism](https://en.wikipedia.org/wiki/Subgraph_isomorphism_problem)
  - [Graph isomorphism](https://en.wikipedia.org/wiki/Graph_isomorphism_problem)


## Algorithms
- [A\* search](https://en.wikipedia.org/wiki/A*_search_algorithm)
- [Best-first search](https://en.wikipedia.org/wiki/Best-first_search)
- [Breadth-first search](https://en.wikipedia.org/wiki/Breadth-first_search)
  - [Level structure](https://en.wikipedia.org/wiki/Level_structure)
  - [Lexicographic breadth-first search](https://en.wikipedia.org/wiki/Lexicographic_breadth-first_search)
- [Depth-first search](https://en.wikipedia.org/wiki/Depth-first_search)
  - [Iterative deepening depth-first search](https://en.wikipedia.org/wiki/Iterative_deepening_depth-first_search)
- [Dijkstra's shortest path first (SPF) algorithm](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
- [Flooding algorithm](https://en.wikipedia.org/wiki/Flooding_algorithm)
- [Hungarian algorithm](https://en.wikipedia.org/wiki/Hungarian_algorithm)
- [Nearest neighbor algorithm](https://en.wikipedia.org/wiki/Nearest_neighbour_algorithm)
  - [*k*-nearest neighbors algorithm](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [Prim's algorithm](https://en.wikipedia.org/wiki/Prim%27s_algorithm)
- [Tarjan's off-line lowest common ancestors algorithm](https://en.wikipedia.org/wiki/Tarjan%27s_off-line_lowest_common_ancestors_algorithm)
