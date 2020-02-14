# [Graph Theory](https://en.wikipedia.org/wiki/Graph_theory)

- A graph is a network of connected nodes (i.e. vertices)..
- A connection with a direction is an arc.
- A connection without a direction is an edge.
- A connection can have a weight or cost.
- A graph with directions is called a [directed graph, or digraph](https://en.wikipedia.org/wiki/Directed_graph).
- A graph with weights is called a weighted graph.
- You may want to visit every node: the [travelling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem).
- You may want to find the [shortest or cheapest path](https://en.wikipedia.org/wiki/Shortest_path_problem).

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

You can also represent a graph as a [dictionary](https://en.wikipedia.org/wiki/Associative_array) of [lists](https://en.wikipedia.org/wiki/List_%28abstract_data_type%29), where each key is a node, and each value is a list of connected nodes.
```python3
graph = {1: [2],
         2: [3, 4],
         3: [4, 5, 6],
         4: [1, 5],
         5: [2]}
```

## Definitions
- [Glossary of graph theory terms](https://en.wikipedia.org/wiki/Glossary_of_graph_theory_terms)
- [Connectivity](https://en.wikipedia.org/wiki/Connectivity_%28graph_theory%29)
- [Coset](https://en.wikipedia.org/wiki/Coset)
- [Graph (abstract data type)](https://en.wikipedia.org/wiki/Graph_%28abstract_data_type%29)
- [Graph (discrete mathematics)](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29)
- [Graph (topology)](https://en.wikipedia.org/wiki/Graph_%28topology%29)
- [Graph algebra](https://en.wikipedia.org/wiki/Graph_algebra)
- [Graph automorphism](https://en.wikipedia.org/wiki/Graph_automorphism)
- [Graph coloring](https://en.wikipedia.org/wiki/Graph_coloring)
- [Graph drawing](https://en.wikipedia.org/wiki/Graph_drawing)
- [Graph enumeration](https://en.wikipedia.org/wiki/Graph_enumeration)
- [Graph equation](https://en.wikipedia.org/wiki/Graph_equation)
- [Graph operations](https://en.wikipedia.org/wiki/Graph_operations)
  - [Graph rewriting](https://en.wikipedia.org/wiki/Graph_rewriting)
- [Graph traversal (i.e. graph search)](https://en.wikipedia.org/wiki/Graph_traversal)
- [Partially ordered set](https://en.wikipedia.org/wiki/Partially_ordered_set)
- [Pathwidth](https://en.wikipedia.org/wiki/Pathwidth)
- [Principle of compositionality](https://en.wikipedia.org/wiki/Principle_of_compositionality)
- [Set (mathematics)](https://en.wikipedia.org/wiki/Set_%28mathematics%29)
  - [Group (mathematics)](https://en.wikipedia.org/wiki/Group_%28mathematics%29)
- [Strongly connected component](https://en.wikipedia.org/wiki/Strongly_connected_component)
- [Transitive reduction](https://en.wikipedia.org/wiki/Transitive_reduction)

## Mathematical Theories
- [Combinatorics](https://en.wikipedia.org/wiki/Combinatorics)
  - [Graph theory](https://en.wikipedia.org/wiki/Graph_theory)
    - [Algebraic graph theory](https://en.wikipedia.org/wiki/Algebraic_graph_theory)
    - [Geometric graph theory](https://en.wikipedia.org/wiki/Geometric_graph_theory)
    - [Extremal graph theory](https://en.wikipedia.org/wiki/Extremal_graph_theory)
    - [Probabilistic graph theory](https://en.wikipedia.org/wiki/Random_graph)
    - [Topological graph theory](https://en.wikipedia.org/wiki/Topological_graph_theory)
- [Group theory](https://en.wikipedia.org/wiki/Group_theory)
- [Network theory](https://en.wikipedia.org/wiki/Network_theory)
- [Set theory](https://en.wikipedia.org/wiki/Set_theory)

## Graph Features
- [Bridge](https://en.wikipedia.org/wiki/Bridge_%28graph_theory%29)
- [Clique](https://en.wikipedia.org/wiki/Clique_%28graph_theory%29)
- [Component](https://en.wikipedia.org/wiki/Component_%28graph_theory%29)
- [Cycle](https://en.wikipedia.org/wiki/Cycle_%28graph_theory%29)
- [Loop](https://en.wikipedia.org/wiki/Loop_%28graph_theory%29)
- [Neighborhood](https://en.wikipedia.org/wiki/Neighbourhood_%28graph_theory%29)
- [Path](https://en.wikipedia.org/wiki/Path_%28graph_theory%29)
- [Vertex](https://en.wikipedia.org/wiki/Vertex_%28graph_theory%29)

## Types of Graph
- [Bipartite graph](https://en.wikipedia.org/wiki/Bipartite_graph) (i.e. bigraph)
- [Cayley graph](https://en.wikipedia.org/wiki/Cayley_graph)
- [Conceptual graph](https://en.wikipedia.org/wiki/Conceptual_graph)
- [Cycle graph](https://en.wikipedia.org/wiki/Cycle_graph)
- [Dense graph](https://en.wikipedia.org/wiki/Dense_graph)
- [Directed graph](https://en.wikipedia.org/wiki/Directed_graph) (i.e. digraph)
  - [Directed acyclic graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph) (i.e. DAG)
    - [Bayesian network](https://en.wikipedia.org/wiki/Bayesian_network)
      - [Dynamic Bayesian network](https://en.wikipedia.org/wiki/Dynamic_Bayesian_network)
  - [Flow network](https://en.wikipedia.org/wiki/Flow_network)
- [Existential graph](https://en.wikipedia.org/wiki/Existential_graph)
- [Hypergraph](https://en.wikipedia.org/wiki/Hypergraph)
- [Lattice graph](https://en.wikipedia.org/wiki/Lattice_graph)
- [Line graph](https://en.wikipedia.org/wiki/Line_graph)
- [Logical graph](https://en.wikipedia.org/wiki/Logical_graph)
- [Mixed graph](https://en.wikipedia.org/wiki/Mixed_graph)
- [Multigraph](https://en.wikipedia.org/wiki/Multigraph)
- [Null graph](https://en.wikipedia.org/wiki/Null_graph) (i.e. edgeless or empty graph)
- [Path graph](https://en.wikipedia.org/wiki/Path_graph) (i.e. linear graph)
- [Perfect graph](https://en.wikipedia.org/wiki/Perfect_graph)
  - [Chordal graph](https://en.wikipedia.org/wiki/Chordal_graph)
- [Planar graph](https://en.wikipedia.org/wiki/Planar_graph)
- [Quantum graph](https://en.wikipedia.org/wiki/Quantum_graph)
- [Random graph](https://en.wikipedia.org/wiki/Random_graph)
- [Regular graph](https://en.wikipedia.org/wiki/Regular_graph)
  - [Strongly regular graph](https://en.wikipedia.org/wiki/Strongly_regular_graph)
- [Schreier coset graph](https://en.wikipedia.org/wiki/Schreier_coset_graph)
- [Symmetric graph](https://en.wikipedia.org/wiki/Symmetric_graph)
- [Undirected graph](https://en.wikipedia.org/wiki/Graph_%28discrete_mathematics%29)
  - [Asymmetric graph](https://en.wikipedia.org/wiki/Asymmetric_graph)
  - [Clique graph](https://en.wikipedia.org/wiki/Clique_graph)
  - [Cograph](https://en.wikipedia.org/wiki/Cograph) (i.e. complement-reducible graph)
    - [Complete graph](https://en.wikipedia.org/wiki/Complete_graph)
      - [Complete bipartite graph](https://en.wikipedia.org/wiki/Complete_bipartite_graph) (i.e. biclique)
        - [Edge-transitive](https://en.wikipedia.org/wiki/Edge-transitive_graph)
          - [Gray graph](https://en.wikipedia.org/wiki/Gray_graph)
  - [Petersen graph](https://en.wikipedia.org/wiki/Petersen_graph)
  - [Semi-symmetric graph](https://en.wikipedia.org/wiki/Semi-symmetric_graph)
  - [Simplex graph](https://en.wikipedia.org/wiki/Simplex_graph)
  - [Tree](https://en.wikipedia.org/wiki/Tree_%28graph_theory%29)
    - [Caterpillar tree](https://en.wikipedia.org/wiki/Caterpillar_tree)
    - [Polytree](https://en.wikipedia.org/wiki/Polytree)
- [Weighted network](https://en.wikipedia.org/wiki/Weighted_network)

## Problems
- [3 utilities](https://en.wikipedia.org/wiki/Three_utilities_problem)
- [7 Bridges of Königsberg](https://en.wikipedia.org/wiki/Seven_Bridges_of_K%C3%B6nigsberg)
- [Art gallery](https://en.wikipedia.org/wiki/Art_gallery_problem)
- [Covering problems](https://en.wikipedia.org/wiki/Covering_problems)
  - [Dominating set](https://en.wikipedia.org/wiki/Dominating_set)
  - [Edge cover](https://en.wikipedia.org/wiki/Edge_cover)
  - [Set cover](https://en.wikipedia.org/wiki/Set_cover_problem)
  - [Vertex cover](https://en.wikipedia.org/wiki/Vertex_cover)
- [Graph sandwich](https://en.wikipedia.org/wiki/Graph_sandwich_problem)
- [Hamiltonian path](https://en.wikipedia.org/wiki/Hamiltonian_path_problem)
- [Maximal flow](https://en.wikipedia.org/wiki/Maximum_flow_problem)
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
- [Ford-Fulkerson algorithm](https://en.wikipedia.org/wiki/Ford%E2%80%93Fulkerson_algorithm)
- [Hungarian algorithm](https://en.wikipedia.org/wiki/Hungarian_algorithm)
- [Nearest neighbor algorithm](https://en.wikipedia.org/wiki/Nearest_neighbour_algorithm)
  - [*k*-nearest neighbors algorithm](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [Prim's algorithm](https://en.wikipedia.org/wiki/Prim%27s_algorithm)
- [Tarjan's off-line lowest common ancestors algorithm](https://en.wikipedia.org/wiki/Tarjan%27s_off-line_lowest_common_ancestors_algorithm)
