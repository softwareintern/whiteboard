# Clone graph
Clone an undirected graph. Each node in the graph contains a label and a list of its neighbors. Nodes are labeled uniquely. We use '#' as a separator for each node and ',' as a separator for node label and each neighbor of the node. As an example, consider the serialized graph {0, 1, 2#1, 2#2, 2}. The graph has a total of three nodes, and therefore contains three parts as separated by #.
  1. first node is labeled as 0. Connect node 0 to both nodes 1 and 2.
  2. second node is labeled as 1. connect node 0 to both nodes 1 and 2.
  3. third node is labeled as 1. connect node 2 to node 2 (itself), thus forming a self cycle.

```
  1
 /  \
0 --- 2
     /_\
```

## sources
  - CP 17 pg. 33
