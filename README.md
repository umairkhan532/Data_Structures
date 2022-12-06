# Data Structure Tutorial : Binary Tree



## I. OVERVIEW

Binary Tree is defined as a Tree data structure with at most 2 children. Since each element in a
binary tree can have only 2 children, we typically name them the left and right child (1). An
implementation of a binary search tree is useful when elements can be compared less than /
greater than each other. For our example, we’ll use alphabetical order as our criteria for
whether an element is greater than or less than another element (eg. “alan” < “bob” < “dave” <
“john” < “kyle” < “leonard” < “zack”). (2)


## II. HOW DOES IT WORK?

![binary, the Binary tree](/Binary1.png)

As shown in the above figure, the binary tree contains at most two child nodes. Binary trees use
the following terms:-

Path: represents the sequence of nodes either on the left or on the right. <br>
Root: A root node is the topmost node of a tree, and each tree has only one root node. For example, A is the root node of the tree. <br>
Parent: Any node except the root node can be considered a parent, for example B. <br>
Child: Below the parent node tree is the child node, for example D and E are children of B. <br>
Leaf: A leaf node is one that does not have any children in a binary tree, for example D. <br>
Key: The key represents the value of a node and is used to search and insert. (3) <br>

Now let’s see the basic operation of the Binary tree as follows:-

### Insert Operation:
The binary tree representation begins with the insertion operation. Then, we insert the node on
its proper location, based on its key value. <br>
Time Complexity: O(n)

![Insert, Insert Operation](/Binary2.png)

(4) <br>

### Search Operation:
Searching an element in a binary tree begins with the root node, then we compare the item
value or element value with the key value. Depending on the search value, we perform the
search left or right, if it is less or greater than the key value. <br>
Time Complexity: O(n)

![Search, Search Operation](/Binary3.png)

(5) <br>

### Deletion Operation:
Given a binary tree, delete a node from it by making sure that the tree shrinks from the bottom. <br>
Time Complexity: O(n)

![Deletion, Deletion Operation](/Binary4.png)

(6) <br>

### Preorder Traversal:
We traverse the node in a pre-order manner as per requirement. <br>
Preorder => Root, Left, Right.

![Preorder, Preorder](/Binary5.png)

(7) <br>

### Inorder Traversal:
We traverse the node in an in-order manner as per requirement. <br> 
Inorder=> Left, Root, Right.

![Inorder, Inorder](/Binary6.png)

(7) <br>
### Postorder Traversal:
We traverse the node in a post-order manner as per requirement. <br>
Post Order=> Left, Right, Root

![Postorder, Postorder](/Binary7.png)

## III. HOW IS THIS DATA STRUCTURE USEFUL?

### Applications of Binary Tree:-
Binary Search Tree - Used in many search applications where data is constantly
entering/leaving, such as the map and set objects in many languages' libraries. <br>

Binary Space Partition - Used in almost every 3D video game to determine what objects need
to be rendered. <br>

Binary Tries - Used in almost every high-bandwidth router for storing router-tables. <br>

Hash Trees - Used in torrents and specialized image-signatures in which a hash needs to be
verified, but the whole file is not available. Also used in blockchains for eg. Bitcoin. <br>

Heaps - Used in implementing efficient priority-queues, which in turn are used for scheduling
processes in many operating systems, Quality-of-Service in routers, and A* (path-finding
algorithm used in AI applications, including robotics and video games). Also used in heap-sort. <br>
(8)

### Why is Binary Tree better than others?
The reason that binary trees are used more often than n-ary trees for searching is that n-ary
trees are more complex, but usually provide no real speed advantage. <br>

In a (balanced) binary tree with m nodes, moving from one level to the next requires one
comparison, and there are log_2(m) levels, for a total of log_2(m) comparisons. <br>

In contrast, an n-ary tree will require log_2(n) comparisons (using a binary search) to move to
the next level. Since there are log_n(m) total levels, the search will require log_2(n)*log_n(m) =
log_2(m) comparisons total. So, though n-ary trees are more complex, they provide no
advantage in terms of total comparisons necessary.
(8)

## IV. FURTHER READING
1. https://www.geeksforgeeks.org/binary-tree-data-structure/
2. https://www.lookfar.com/blog/2016/07/28/why-binary-search-trees-matter/
3. https://www.educba.com/binary-tree-in-data-structure/
4. https://www.geeksforgeeks.org/insertion-in-a-binary-tree-in-level-order/
5. https://www.geeksforgeeks.org/search-a-node-in-binary-tree/
6. https://www.geeksforgeeks.org/deletion-binary-tree/
7. https://www.gatevidyalay.com/tree-traversal-binary-tree-traversal/
8. https://stackoverflow.com/questions/2130416/what-are-the-applications-of-binarytrees
9. https://www.javatpoint.com/binary-tree <br>
10.https://www.w3schools.in/data-structures/binary-trees
