# C - Binary trees

This was a group project in which we learnt about the details, advantages,
and disadvantages of using trees as data structures. We learned about how to
qualify trees as well as how to traverse them. Throughout the project, we
implemented binary, binary search, AVL, and Max Binary Heap trees.

## Tasks :page_with_curl:

* **0. New node**
  * [0-binary_tree_node.c](./0-binary_tree_node.c): C function that creates a
  binary tree node with a given parent and value.
  * Returns a pointer to the new node, or `NULL` on failure.

* **1. Insert left**
  * [1-binary_tree_insert](./1-binary_tree_insert): C function that inserts a
  node as the left-child of another.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the given `parent` already contains a left node, the new node takes its
  place and the old left-child becomes the left-child of the new node.

* **2. Insert right**
  * [2-binary_tree_insert_right.c](./2-binary_tree_insert_right.c): C function that
  inserts a node as the right-child of another.
  * Returns a pointer to the new node, or `NULL` on failure.
  * If the given `parent` already contains a right node, the new node takes its
  place and the old right-child becomes the right-child of the new node.
