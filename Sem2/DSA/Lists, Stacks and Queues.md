# Linked list vs Arrays

1. Linked list: elements not stored in contiguous memory locations. We can't access any element with O(1) complexity. Inefficient for larger data sets. Don't use it if you're depending on fast retrieval.
2. Advantage: Dynamic. We don't have to worry about the size, we can append and insert.
(check linkedlist.c to revise)


## Stacks

Once you learn stacks, it's pretty easy to learn queues.
Recall what you learnt in static memory allocation.

### What is a stack?

1. A linear data structure that follows Last In First Out Principle(LIFO)
2. One can remove the element on top, or add an element at the topmost position of the stack
3. To remove any other element, one must remove all the elements on top of it.

### Basic stack operations

1. Push : adds element on top
2. Pop : removes element from the top
3. isEmpty : checks if stack is empty
4. isFull : checks if it is full
5. Peek: gets the value of the top element without modifying it.
All these operations can be performed with O(1) - constant time complexity


### Working

1. A pointer keeps track of the topmost element
2. pointer is initialized to -1 so as to indicate it as an empty stack

![[Pasted image 20231212224958.png]]
3. check if stack is full before pushing, and check if empty before popping

