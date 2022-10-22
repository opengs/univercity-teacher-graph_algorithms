# BFS and DFS

## BFS
Link to the [wiki](https://en.wikipedia.org/wiki/Breadth-first_search)
Pseudocode:
```
 1  procedure BFS(G, root) is
 2      let Q be a queue
 3      label root as explored
 4      Q.enqueue(root)
 5      while Q is not empty do
 6          v := Q.dequeue()
 7          if v is the goal then
 8              return v
 9          for all edges from v to w in G.adjacentEdges(v) do
10              if w is not labeled as explored then
11                  label w as explored
12                  Q.enqueue(w)
```

## DFS
Link to the [wiki](https://en.wikipedia.org/wiki/Depth-first_search)
Pseudocode
```
procedure DFS(G, v) is
    label v as discovered
    for all directed edges from v to w that are in G.adjacentEdges(v) do
        if vertex w is not labeled as discovered then
            recursively call DFS(G, w)
```

## Assignments
0. [DFS](https://leetcode.com/problems/path-sum/)
1. [DFS](https://leetcode.com/problems/maximum-depth-of-n-ary-tree/)
2. [BFS](https://leetcode.com/problems/flood-fill/)

For more tasks visit [DFS](https://leetcode.com/tag/depth-first-search/) and [BFS](https://leetcode.com/tag/breadth-first-search/) pages