# EulerianPathCircuit

Graph Theory Project 1 (Fall 2021): Finding Eulerian Path & Circuit for Undirected Graphs.
This is the code that I write for Graph Theory Project 1 (Fall 2021).

Eulerian Path is a path in graph that visits every edge exactly once. 
Eulerian Circuit is an Eulerian Path which starts and ends on the same vertex. 

How to use this code?:
1) Construct the graph with number of edges you want using the syntax below.
    Graph "graph_name" = new Graph("number_of_edges")
    
2) Add an edge between vertices using the syntax below.
    graph_name.addEdge("edge1", "edge2")
    
3)  Run the test class with your graph in the main method.
    graph_name.test()
