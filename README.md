# binary_trees

A binary tree is a data structure composed of nodes, where each node has at most two children, referred to as the left child and the right child. The topmost node of the tree is called the root, and nodes with no children are called leaf nodes. Binary trees are used to represent hierarchical structures efficiently.

The main difference between a binary tree and a Binary Search Tree (BST) lies in the rules governing the arrangement of nodes. In a BST, for every node, all nodes in its left subtree have values less than its own value, and all nodes in its right subtree have values greater than its own value. This property makes searching, insertion, and deletion operations more efficient in a BST compared to a regular binary tree.

The possible gain in terms of time complexity compared to linked lists is significant, especially for search, insertion, and deletion operations. In a linked list, the time complexity for these operations is O(n) in the worst case, where n is the number of elements in the list. However, in a balanced binary search tree, the time complexity for these operations is O(log n) in the worst case, where n is the number of elements in the tree. This difference arises from the logarithmic height of the balanced BST, which allows for efficient traversal and searching.

In a binary tree:
- Depth: The depth of a node is the number of edges from the root to that node. The depth of the root node is 0.
- Height: The height of a node is the number of edges from the node to the deepest leaf node in its subtree. The height of a tree is the height of the root node.
- Size: The size of a binary tree is the total number of nodes it contains.

There are three main traversal methods to go through a binary tree:
1. In-order traversal: Visit the left subtree, then the root node, and finally the right subtree.
2. Pre-order traversal: Visit the root node, then the left subtree, and finally the right subtree.
3. Post-order traversal: Visit the left subtree, then the right subtree, and finally the root node.

A complete binary tree is a binary tree in which all levels are completely filled, except possibly the last level, and all nodes on the last level are as far left as possible.

A full binary tree is a binary tree in which every node has either 0 or 2 children, meaning there are no nodes with only one child.

A perfect binary tree is a binary tree that is both full and complete. In a perfect binary tree, all internal nodes have exactly two children, and all leaf nodes are at the same level.

A balanced binary tree is a binary tree in which the difference in height between the left and right subtrees of every node is at most one. This balance ensures that the time complexity of operations remains O(log n), providing efficient performance for various operations on the tree.
