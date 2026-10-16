# Abraham Kilwake-190400, Natalie Shalo-, Wachira Christine-


## Question 2: Kenya Highway Network: Directed Graph and Search Tree
### Nodes are states and arcs are actions. Every highway can be driven in both directions, so each road is represented by two directed arcs (A→B and B→A) with the same cost.
![picture a](images/kenya_graph.png)

## Search Tree
### The root is the initial state and each branch is an action (a drive to the next town). g is the cumulative path cost. ✂ marks a branch that is left out by abstraction and not expanded. Going back to the town just left is also omitted, since it only creates loops
![picture 2](images/kenya_tree.png)