# shortest-path-algo
Key Features of the Graph
  Nodes: Each key in the dictionary represents a unique node in the graph (e.g., 'A', 'B', 'C', etc.).
  Edges: The value associated with each node is a list of tuples. Each tuple contains:
  A neighboring node.
  The weight (or distance) of the edge connecting the current node to the neighbor.
Example:
  The entry for node 'A' indicates it is connected to:
  Node 'B' with a weight of 5.
  Node 'C' with a weight of 3.
  Node 'E' with a weight of 11.
Function: shortest_path
  Parameters
    graph: The graph represented as an adjacency list (as shown above).
    start: The starting node from which to calculate the shortest paths.
    target: (Optional) A specific target node to find the shortest path to. If not provided, the function will calculate and print distances to all nodes.
Returns
  A tuple containing:
  distances: A dictionary mapping each node to its shortest distance from the start node.
  paths: A dictionary mapping each node to the list of nodes that make up the shortest path from the start node.
