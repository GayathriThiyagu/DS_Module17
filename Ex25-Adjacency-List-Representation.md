# Ex25 Adjacency List Representation
## AIM:
To write a C program to represent the given graph using the adjacency list.

## Algorithm
1. Initialize variables
2. Read the number of vertices
3. Input edges of the graph
4. Construct the graph
5. Print the graph
6. End the graph

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: T. Gayathri
RegisterNumber:  212223100007

int main(void)
{   int n,i;
    scanf("%d",&N);
    scanf("%d",&n);
    // input array containing edges of the graph (as per the above diagram)
    // (x, y) pair in the array represents an edge from x to y
    struct Edge edges[n];
    for (i = 0; i < n; i++)
    {
        // get the source and destination vertex
        scanf("%d",&edges[i].src);
        scanf("%d",&edges[i].dest);
      
    }
   
    // construct a graph from the given edges
    struct Graph *graph = createGraph(edges, n);
 
    // Function to print adjacency list representation of a graph
    printGraph(graph);
 
    return 0;
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/fdd859d7-7eb0-456c-b2c9-d149527e2e13)


## Result:
Thus, the C program to represent the given graph using the adjacency list is implemented successfully
