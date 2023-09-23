# BMTC
Bangalore bus It's a Java program that will take name of the source bus stand and the destination bus stand of Bangalore Bus, from the user and display the fare and shortest bus route to reach the destination. The idea is implemented using Graph and Heap data structures.
This is a simple Java program that will take information (name) of the source stand and the destination stand, of Bangalore bus stand, from the user and display the fare and shortest bus route to reach the destination. 

The idea is implemented using Graph and Heap data structures. The graph has nodes and edges. Nodes represent a metro station that will be containing certain information regarding that station like its name, its bus route, and the lines which it connects. Edges (the connection between two nodes) represent the distance between the two stations and the cost of each edge will be equal to the distance between the two of its connecting stations(nodes).

By using different algorithms like Dijkstra, breadth-first search, depth-first search, etc, the shortest path between the source station and the destination station is determined, and accordingly, the fare is being calculated on the basis of the total distance between the two stations. Finally, the bus route between the two stations and the total fare is displayed.

Main.java cointains all the major code and Heap.java contains heap implementation.
