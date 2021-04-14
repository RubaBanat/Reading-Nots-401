# Trees


**Tree represents the nodes connected by edges**


---


![trees](imgs/tree-data-struct.png)


---

## Important Terms


Word | Definition 
------------ | -------------
Path | Path refers to the sequence of nodes along the edges of a tree.
Root | The node at the top of the tree is called root. There is only one root per tree and one path from the root node to any node.
Parent  | Any node except the root node has one edge upward to a node called parent..
Child |  The node below a given node connected by its edge downward is called its child node.
Leaf  |  The node which does not have any child node is called the leaf node.
Subtree  |Subtree represents the descendants of a node.
Visiting  |Visiting refers to checking the value of a node when control is on the node.
Traversing  |  Traversing means passing through nodes in a specific order.
Levels  | Level of a node represents the generation of a node. If the root node is at level 0, then its next child node is at level 1, its grandchild is at level 2, and so on.
keys  | Key represents a value of a node based on which a search operation is to be carried out for a node

---

## Binary Search Tree

 **Binary Search tree exhibits a special behavior. A node's left child must have a value less than its parent's value and the node's right child must have a value greater than its parent value.**


![BinaryTree](imgs/Binary.png)


---

## BST Basic Operations


**The basic operations that can be performed on a binary search tree data structure, are the following**


- `Insert` :  Inserts an element in a tree/create a tree.

- `Search` : Searches an element in a tree.

- `Preorder Traversal` : Traverses a tree in a pre-order manner.

- `Inorder Traversal` : Traverses a tree in an in-order manner.

- `Postorder Traversal` : Traverses a tree in a post-order manner.

---

## Breadth First 

**Breadth first traversal iterates through the tree by going through each level of the tree node-by-node**

**Traditionally, breadth first traversal uses a queue to traverse the width/breadth of the tree. Let’s break down the process.**


![BreadthFirst](imgs/BreadthFirst.jpeg)

---

## K-ary Trees

**If Nodes are able have more than 2 child nodes, we call the tree that contains them a K-ary Tree. In this type of tree we use K to refer to the maximum number of children that each Node is able to have.**

---

## Big O

**The Big O time complexity of a Binary Search Tree’s insertion and search operations is O(h), or O(height).**

**The Big O space complexity of a BST search would be O(1). During a search, we are not allocating any additional space.**


---

# THE END