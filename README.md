# Kosaraju's Algorithm : O(V+E)

Kosaraju's algorithm is used to find the strongly connected components(SCC) in a graph.

It makes use of the fact that the transpose graph (the same graph with the direction of every edge reversed) has exactly the same strongly connected components as the original graph.

## Strongly Connected Component :
If we can reach every vertex of a component from every other vertex in that component then it is called a Strongly Connected Component (SCC).

## Algorithm
1. Use first DFS to fill the stack with vertex
2. Reverse the edges of the original graph
3. Pop the vertex from the stack(filled in step 1), until its empty, call the second DFS to find the size of the strongly connected component.


# References :
1. https://www.youtube.com/watch?v=QtdE7QPsWiU (Hindi, Good explanation)






