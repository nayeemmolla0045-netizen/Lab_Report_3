The program reads from a file called input.txt which contains
N M K representing the number of vertices, edges, and available colors
The graph is represented as a dictionary of list. Start from the first vertex (0). Try all colors from 1 to K for the current vertex. For a chosen color, check all adjacent vertices to ensure no neighbor has the same color
If no valid color is available for a vertex, backtrack to the previous vertex and try a different color.
Repeat until all vertices are colored or all possibilities are exhausted.
