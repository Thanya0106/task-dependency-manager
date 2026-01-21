# Circular Dependency Detection

## Approach
- Model tasks as a directed graph
- Each dependency is an edge
- DFS is used to detect cycles

## Algorithm
- Start DFS from the new dependency
- Track visited and recursion stack
- If a node appears again in stack → cycle detected

## Time Complexity
O(V + E)

## Why DFS?
- Simple
- Efficient
- Easy to trace exact cycle path
