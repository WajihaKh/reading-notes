# Tree Cheat Sheet

## Common Terminology

- **Node**: A component of a tree that may contain its own values and references to other nodes.
- **Root**: The starting node of the tree.
- **K**: The maximum number of children any node may have in a k-ary tree. For binary trees, k = 2.
- **Left**: A reference to one child node in a binary tree.
- **Right**: A reference to the other child node in a binary tree.
- **Edge**: The link between a parent and child node.
- **Leaf**: A node without any children.
- **Height**: The number of edges from the root to the furthest leaf.

## Traversals

### Depth First

1. **Pre-order**: root >> left >> right
2. **In-order**: left >> root >> right
3. **Post-order**: left >> right >> root

### Breadth First

- Iterates through each level of the tree node-by-node.

## Binary Tree Vs K-ary Trees

- **Binary Tree**: Restricts the number of children to two (left and right).
- **K-ary Trees**: Nodes can have more than two child nodes.

## Big O

- **Insertion Time Complexity**: O(n)
- **Searching Time Complexity (BST)**: O(h) (height of the tree)
- **Space Complexity**: O(w) (width of the tree)

## Binary Search Trees (BST)

- Nodes are organized such that smaller values are placed to the left and larger values to the right of the root.
