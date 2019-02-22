# HeapSort

> Notes taken from [Vaidehi Joshi's](https://medium.com/@vaidehijoshi) [Heapify All The Things With Heap Sort](https://medium.com/basecs/heapify-all-the-things-with-heap-sort-55ee1c93af82)

* What is HeapSort?
  * An algorithm to sort using a heap data structure and sorting the root (maxValue) at the end of the unsorted collection.

* What are the steps for heap sort?
  1. Build max heap (build max heap function)
  2. Swap first and last nodes
  3. Maintain heap order property by bubbling down node using heapify function

* What is the run time to build MaxHeap?
  * O(n) --> all items added to heap

* What is the run time of heapify?
  * O(log n)

* Runtime of heap sort?
  * O(n log n)

* What is the space complexity of heapsort?
  * O(1) --> In Place

* Is HeapSort stable?
  * No (deals with duplicates - can't guarantee its in order)

* Is heap sort recursive?
  * No
