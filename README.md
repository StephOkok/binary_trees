# Binary Trees #

A binary tree is a data structure in which each node has at most two children, which are referred to as the left child and the right child.

Binary trees can be implemented in at least two ways: as arrays and as linked structures.
To implement a tree as an array, a node is declared as a structure with an information
field and two “pointer” fields. These pointer fields contain the indexes of the array cells
in which the left and right children are stored, if there are any.

# Important Terms #

Following are the important terms with respect to tree.
1. Path − Path refers to the sequence of nodes along the edges of a tree.
2. Root − The node at the top of the tree is called root. There is only one root per tree and one path from the root node to any node.
3. Parent − Any node except the root node has one edge upward to a node called parent.
4. Child − The node below a given node connected by its edge downward is called its child node.
5. Leaf − The node which does not have any child node is called the leaf node.
6. Subtree − Subtree represents the descendants of a node.
7. Visiting − Visiting refers to checking the value of a node when control is on the node.
8. Traversing − Traversing means passing through nodes in a specific order.
9. Levels − Level of a node represents the generation of a node. If the root node is at level 0, then its next child node is at level 1, its grandchild is at level 2, and so on.
10. keys − Key represents a value of a node based on which a search operation is to be carried out for a node.

# Binary Search Tree Representation #

Binary Search tree exhibits a special behavior. A node's left child must have a value less than its parent's value and the node's right child must have a value greater than its parent value.
Binary Search Tree

*Tree Traversal* - inorder, preorder and postorder
1. Inorder traversal

    First, visit all the nodes in the left subtree
    Then the root node
    Visit all the nodes in the right subtree

2. Preorder traversal

    Visit root node
    Visit all the nodes in the left subtree
    Visit all the nodes in the right subtree

3. Postorder traversal

    Visit all the nodes in the left subtree
    Visit all the nodes in the right subtree
    Visit the root node
















