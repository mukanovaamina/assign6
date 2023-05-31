# assign6
Mukanova Amina, SE-2215

#Main method: 

main(String[] args) method: Serves as the entry point of the program and executes the main logic. 

addEdge(int source, int destination) method in the WeightedGraph class: Adds a weighted edge between two vertices in the graph. 

printGraph() method in the WeightedGraph class:Prints the graph by displaying the vertices and their adjacent vertices. search(int 

startVertex) method in the Search interface:Defines the search method that will be implemented by different search algorithms. 

BreadthFirstSearch class:Implements the BFS algorithm for searching in a graph. DijkstraSearch class: Implements Dijkstra's algorithm for searching in a weighted graph.


#BreadthFirstSearch class: 

BreadthFirstSearch(WeightedGraph graph) constructor:Initializes the BreadthFirstSearch object with the provided WeightedGraph. 

search(int startVertex) method:Performs the breadth-first search algorithm starting from the specified startVertex.


#DijkstraSearch class: 

DijkstraSearch(WeightedGraph graph) constructor: Initializes the DijkstraSearch object with the provided WeightedGraph. 

search(int startVertex) method:Performs Dijkstra's algorithm starting from the specified startVertex. 

getWeight(int source, int destination) method:Returns the weight of the edge between the source and destination vertices. 

printShortestPaths(int startVertex, double[] distances, int[] previous) method: Prints the shortest paths and distances from the startVertex to all other vertices.

printPath(int vertex, int[] previous) method: Recursively prints the path from the startVertex to the given vertex.


#Search class: 

search(int startVertex) method:Defines the search algorithm that will be implemented by classes that implement this interface.


#Vertex class: 

Vertex(T value) constructor: Initializes a Vertex object with the provided value. 

getValue() method:Returns the value associated with the vertex.


#VertexDistancePair class: 

VertexDistancePair(int vertex, double distance) constructor: Initializes a VertexDistancePair object with the provided vertex and distance values. 

getVertex() method:Returns the vertex value associated with the VertexDistancePair.

getDistance() method:Returns the distance value associated with the VertexDistancePair. 

compareTo(VertexDistancePair other) method:Implements the compareTo method from the Comparable interface.


#WeightedGraph class:

WeightedGraph(int numOfVertices) constructor:Initializes a WeightedGraph object with the provided number of vertices. 

addEdge(int source, int destination) method:Adds a weighted edge between the source and destination vertices. 

removeEdge(int source, int destination) method:Removes the weighted edge between the source and destination vertices. 

hasEdge(int source, int destination) method:Checks if there is a weighted edge between the source and destination vertices. 

getNeighbor(int vertex) method:Returns a linked list of neighboring vertices for a given vertex. 

printGraph() method:Prints the graph by iterating over each vertex and its neighboring vertices. 

validateVertex(int index) method: Validates if the given vertex index is within the valid range.
