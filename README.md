# 0x1D. C - Binary trees


## Learning Objectives
### General
* What is a binary tree
* What is the difference between a binary tree and a Binary Search Tree
* What is the possible gain in terms of time complexity compared to linked lists
* What are the depth, the height, the size of a binary tree
* What are the different traversal methods to go through a binary tree
* What is a complete, a full, a perfect, a balanced binary tree

### Resources
* [Binary tree](https://alx-intranet.hbtn.io/rltoken/1F2x42-8vUbOmU4L1C1KMg) (note the first line: Not to be confused with B-tree.)
* [Data Structure and Algorithms - Tree](https://alx-intranet.hbtn.io/rltoken/QmcTMCkQyrgMjrqoWxYdhw)
* [Tree Traversal](https://alx-intranet.hbtn.io/rltoken/nMxoYQdZR_guroan8JeqBQ)
* [Binary Search Tree](https://alx-intranet.hbtn.io/rltoken/qO5dBlMnYJzbaWG3xVpcnQ)
* [Data structures: Binary Tree](https://alx-intranet.hbtn.io/rltoken/BeyJ2gjlE7_djwRiDyeHig)

## Requirements
* Allowed editors: vi, vim, emacs
* All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
* You are not allowed to use global variables
* No more than 5 functions per file
* You are allowed to use the standard library
* In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
* The prototypes of all your functions should be included in your header file called binary_trees.h
* Don’t forget to push your header file
* All your header files should be include guarded


## More Info
### Data structures
Please use the following data structures and types for binary trees. Don’t forget to include them in your header file.

### Basic Binary Tree
```
/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
```

### Binary Search Tree
```
typedef struct binary_tree_s bst_t;
```

### AVL Tree
```
typedef struct binary_tree_s avl_t;
```

### Max Binary Heap
```
typedef struct binary_tree_s heap_t;
```

**Note:** For tasks 0 to 23 (included), you have to deal with simple binary trees. They are not BSTs, thus they don’t follow any kind of rule.


### Print function
To match the examples in the tasks, you are given [this](https://github.com/holbertonschool/0x1C.c) function

This function is used only for visualization purposes. You don’t have to push it to your repo. It may not be used during the correction

## Usage:
Use the c files in the ./testFiles to excute the binary tree programs according to the module
discription below.

## Module Discription:
**0-binary_tree_node.c:
Function that creates a binary tree node

**1-binary_tree_insert_left.c:  
Function that inserts a node as the left-child of another node

**2-binary_tree_insert_right.c:**
A Function that inserts a node as the right-child of another node

**3-binary_tree_delete.c:**
A Function that deletes an entire binary tree

**4-binary_tree_is_leaf.c:**
A Function that checks if a node is a leaf

**5-binary_tree_is_root.c:**
A Function that checks if a given node is a root

**6-binary_tree_preorder.c:**
A Function that goes through a binary tree using pre-order traversal

**7-binary_tree_inorder.c:**
A Function that goes through a binary tree using in-order traversal

**8-binary_tree_postorder.c:**
A Function that goes through a binary tree using post-order traversal

**9-binary_tree_height.c:**
A Function that measures the height of a binary tree

**10-binary_tree_depth.c:**
A Function that measures the depth of a node in a binary tree

**11-binary_tree_size.c:**
A Function that measures the size of a binary tree

**12-binary_tree_leaves.c:**   
A Function that counts the leaves in a binary tree

**13-binary_tree_nodes.c:**
A Function that counts the nodes with at least 1 child in a binary tree

**14-binary_tree_balance.c:**
A Function that measures the balance factor of a binary tree

**15-binary_tree_is_full.c:**
A Function that checks if a binary tree is full

**16-binary_tree_is_perfect.c:**
A Function that checks if a binary tree is perfect

**17-binary_tree_sibling.c:**
A Function that finds the sibling of a node

**18-binary_tree_uncle.c:**
A Function that finds the uncle of a node

