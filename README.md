- cycle_hpgraph: Functions to find hyperdeges that form cycles in a hypergraph. First, a graph associated to the nodes in the intersection of hyperedges and these hyperedges is created. From this graph, a list of hyperedges forming cycles is made. 
                 
- nodes_cover: From the incident matrix of a hypergraph and a list of hyperedges, it returns the list of nodes covered by these hyperedges.

- random_hgraph_generator: Based on Algorithm 1 in "How do hyperedges overlap in real-world hypergraphs?-patterns, measures, and generators" by G Lee, M Choe, K Shin. From the number of nodes n, number of hyperedges m and the maximum cardinality of hyperedges d, algorithm generates the incident matrix of a hypergraph.
