Answer the following questions for each of the data structures you implemented as part of this project.

## Stack

1. What is the runtime complexity of `push` using a list?
    The runtime complexity is O(1), amortized.

2. What is the runtime complexity of `push` using a linked list?
    The runtime complexity is always O(1).

3. What is the runtime complexity of `pop` using a list?
    The runtime complexity is always O(1).

4. What is the runtime complexity of `pop` using a linked list?
    The runtime complexity is always O(1).

5. What is the runtime complexity of `len` using a list?
    The runtime complexity is always O(1).

6. What is the runtime complexity of `len` using a linked list?
    The runtime complexity is O(n).

## Queue

1. What is the runtime complexity of `enqueue` using a list?
    The runtime complexity is O(n).

2. What is the runtime complexity of `enqueue` using a linked list?
    The runtime complexity is O(1).

3. What is the runtime complexity of `dequeue` using a list?
    The runtime complexity is O(n).

4. What is the runtime complexity of `dequeue` using a linked list?
    The runtime complexity is O(1).

5. What is the runtime complexity of `len` using a list?
    The runtime complexity is O(1).

6. What is the runtime complexity of `len` using a linked list?
    The runtime complexity is O(1).

## Doubly Linked List

1. What is the runtime complexity of `ListNode.insert_after`?
    The runtime complexity is O(1).

2. What is the runtime complexity of `ListNode.insert_before`?
    The runtime complexity is O(1).

3. What is the runtime complexity of `ListNode.delete`?
    The runtime complexity is O(1).

4. What is the runtime complexity of `DoublyLinkedList.add_to_head`?
    The runtime complexity is O(1).

5. What is the runtime complexity of `DoublyLinkedList.remove_from_head`?
    The runtime complexity is O(1).

6. What is the runtime complexity of `DoublyLinkedList.add_to_tail`?
    The runtime complexity is O(1).

7. What is the runtime complexity of `DoublyLinkedList.remove_from_tail`?
    The runtime complexity is O(1).

8. What is the runtime complexity of `DoublyLinkedList.move_to_front`?
    The runtime complexity is O(1).

9. What is the runtime complexity of `DoublyLinkedList.move_to_end`?
    The runtime complexity is O(1).

10. What is the runtime complexity of `DoublyLinkedList.delete`?
    The runtime complexity is O(1).

    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the JS `Array.splice` method. Which method generally performs better?
        The doubly linked list is O(1) meaning that the performance of the doubly linked list will be better on large datasets.

## Binary Search Tree

1. What is the runtime complexity of `insert`?
    The runtime complexity is O(h), where h is the height of the tree.
    If the tree is balanced, this means that insert is O(log n).

2. What is the runtime complexity of `contains`?
    The runtime complexity is O(h), where h is the height of the tree.
    If the tree is balanced, this means that insert is O(log n).

3. What is the runtime complexity of `get_max`? 
    The runtime complexity is O(h), where h is the height of the tree.
    If the tree is balanced, this means that insert is O(log n).

4. What is the runtime complexity of `for_each`?
    The runtime complexity is O(n).
    
## Heap

1. What is the runtime complexity of `_bubble_up`?
    The runtime complexity is O(log n).

2. What is the runtime complexity of `_sift_down`?
    The runtime complexity is O(log n).

3. What is the runtime complexity of `insert`?
    The runtime complexity is O(n).

4. What is the runtime complexity of `delete`?
    The runtime complexity is O(log n).

5. What is the runtime complexity of `get_max`?
    The runtime complexity is O(1).