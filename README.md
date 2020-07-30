# Data-Structure

A data structure is a way of organizing the data so that the data can be used efficiently. Different kinds 

of data structures are suited to different kinds of applications, and some are highly specialized to specific tasks. 

Data structure is important to store data, but way of storing the data is more important than storing the data.

**Linear data structure:** A data structure is said to be linear if its elements form a sequence or a linear list. 

Examples: Array. Linked List, Stacks and Queues

**Non-Linear data structure:** A data structure is said to be non-linear if traversal of nodes is nonlinear in nature. 

Example: Graph and Trees.

**Arrays:** An array is a collection of items stored at contiguous memory locations. The idea is to store multiple items of the same type together. 

This makes it easier to calculate the position of each element by simply adding an offset to a base value, i.e., the memory location of the first 

element of the array (generally denoted by the name of the array).

**Linked lists:**

Like arrays, linked lists store data elements in sequential order. Instead of keeping indexes, linked lists hold pointers to other elements. The first node is called the head while the last node is called the tail. In a singly-linked list, a pointer to the previous node is also kept.

Like arrays, linked lists can operate as stacks. Head is the only place for insertion and removal. In a doubly-linked list linked lists can also operate as queues, where insertion occurs at the tail and removal occurs at the head, or vice-versa.

Linked lists are useful on both the client and server. On the client, state management libraries like Redux structure its middleware logic in a linked-list fashoin. On the server, web frameworks like Express also structure its middleware logic in a similar fashion.

**Queue:**

Queues are arrays with two primary operations: unshift and pop. Unshift enqueues items to the end of the array, while Pop dequeues them from the beginning of the array. In other words, Queues follow the "First In, First Out" protocol (FIFO).If the direction is reversed, we can replace unshift and pop with push and shift, respectively.


**Stacks:**

 Stack is just an array with two principled operations: push and pop. Push add elements to the top of the array, while pop removes them from the same location. Stack follows the "Last In, First Out" protocol (LIFO). Most important stack in JS is the call stack where we push in the scope of a function whenever we execute it. Pro of using a linked list: The stack grows according to the user’s requirements.
Con of using a linked list: Extra memory required to store the pointers.

 
