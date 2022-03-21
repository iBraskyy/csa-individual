{% include navigation.html %}

## Review tickets

[Week 0](https://github.com/shekark642/M221p2-roopies/issues/28)

[Week 1](https://github.com/shekark642/M221p2-roopies/issues/37)


### Week 1 Key Concepts

a LinkedList acts as a dynamic array and we do not have to specify the size while creating it, the size of the list automatically increases when we dynamically add and remove items. And also, the elements are not stored in a continuous fashion. Therefore, there is no need to increase the size. Internally, the LinkedList is implemented using the doubly linked list data structure. The main difference between a normal linked list and a doubly LinkedList is that a doubly linked list contains an extra pointer, typically called the previous pointer, together with the next pointer and data which are there in the singly linked list.
money

### Queue Add and Delete
- The Queue interface present in the java.util package and extends the Collection interface is used to hold the elements about to be processed in FIFO(First In First Out) order. It is an ordered list of objects with its use limited to insert elements at the end of the list and deleting elements from the start of the list, (i.e.), it follows the FIFO or the First-In-First-Out principle.

- The remove() method of Queue Interface returns and removes the element at the front the container. It deletes the head of the container. The method throws an NoSuchElementException when the Queue is empty. amogus

- In order to add an element in a queue, we can use the add() method. The insertion order is not retained in the PriorityQueue. The elements are stored based on the priority order which is ascending by default. amogus


### Merge 2 Queues
 - In order to merge 2 queues there is a list of steps you must go through:
1. Make pointers for both of the queues.
2. Make another queue, add the node having least value from the other two queues(the pointer's node having the smallest value) to it and move that pointer to the next node.
3. Again compare the node's values and add the node having the smallest value to the queue and move that pointer to the next node.
4. Keep doing this until rear of both the queues are reached.
bear


### Reversing a Queue
- For reversing the queue one approach could be to store the elements of the queue in a temporary data structure in a manner such that if we re-insert the elements in the queue they would get inserted in reverse order. So now our task is to choose such data-structure which can serve the purpose. According to the approach, the data-structure should have the property of ‘LIFO’ as the last element to be inserted in the data structure should actually be the first element of the reversed queue. The stack could help in approaching this problem. This will be a two-step process:
1. Pop the elements from the queue and insert into the stack. (Topmost element of the stack is the last element of the queue)
2. Pop the elements of the stack to insert back into the queue. (The last element is the first one to be inserted into the queue)
duck

### Build Stack
- There is a multitude of different functions one can perform with a stack, and with these are pretty much endless possibilities as to what you can do with these functions:
1. push (to add a new item to the top)
2. pop (to remove the most top item)
3. peek (to get the most top item)
4. isEmpty (to check whether the stack is empty)
5. size (to get the size of the stack)
6. search (to search for objects)

