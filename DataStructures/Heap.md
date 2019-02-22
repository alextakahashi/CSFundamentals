# Heap Notes

> Notes taken from [Vaidehi Joshi's](https://medium.com/@vaidehijoshi) [Learning to Love Heaps](https://medium.com/basecs/learning-to-love-heaps-cef2b273a238)

* What is a heap?
  * A Binary Tree w/ 2 properties
    1. All nodes in specific order: root must be >= all children (max-heap)
    2. Shape must be complete

* What does a complete tree look like?
  * Every single level of the tree must be filled
  * Exception last level does not have to be complete but filled left to right

> Heaps can have duplicate values.  Does not necessarily have to follow rules of BST

* What is the heap order property?
  * Ordering of the parent nodes compared to children (min heap vs max heap)

* Where do we add a node to a heap?
  * Left & Bottom most available spot in tree.  Maintain Heap Order Property by swapping

* How do we remove from the heap?
  1. Remove the root node
  2. Place the bottom right most node in root.
  3. Swap children until heap maintains Heap Order Property

* What is the most important characteristic of a heap?
  * Maximum/Minimum always the root node
  * Represented as an array, it is the zero-th element

* Given index of a node in the heap, what is the index of its left and right child.
  * Left: 2i + 1
  * Right: 2i + 2

* Why are heaps often implemented as arrays?
  * Very efficient way of representing a priority Queue

* What is the run time of removing min/max element from the heap?
  * O(1) --> min & max are inherently at the zero-th index

* What is the run time of insertion & deletion
  * O(log n) --> inherent tree structure
