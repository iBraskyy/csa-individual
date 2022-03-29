{% include navigation.html %}

## Review tickets

[Week 0](https://github.com/shekark642/M221p2-roopies/issues/28)

[Week 1](https://github.com/shekark642/M221p2-roopies/issues/37)

[Week 2](https://github.com/shekark642/M221p2-roopies/issues/41)


### Calculator

Linked Lists are a type of data structure in which each piece of data contains a reference link to the next piece of data, meaning that the next node can be referenced through the cucrent node
In our code, generic T was used because we did not know which data types would be inputed into the queue, and so it allows us to use the data without specifically defining a data type
   We used stacks in order to implement Reverse Polish Notation to create the calculator object.
   
   <img width="1440" alt="Screen Shot 2022-03-29 at 9 59 10 AM" src="https://user-images.githubusercontent.com/72888867/160665830-2b6eda60-783b-43a1-b5d1-8ed2eeff98ff.png">
   
   
   Here you can see that I am creating the argument constructor which will be expecting a mathematical expression
   


<img width="1440" alt="Screen Shot 2022-03-29 at 9 59 25 AM" src="https://user-images.githubusercontent.com/72888867/160665866-ca725240-0395-43d1-92d4-50d8a1793fb6.png">


Below you can see how the function takes tokens and converts it to reverse polish notation, where an operator follows operands 


<img width="1440" alt="Screen Shot 2022-03-29 at 10 00 10 AM" src="https://user-images.githubusercontent.com/72888867/160666002-3ed21c7a-6272-4761-a91d-7786a694cc07.png">


The code below takes reverse polish notation and produces our desired result from it 

<img width="1440" alt="Screen Shot 2022-03-29 at 10 01 08 AM" src="https://user-images.githubusercontent.com/72888867/160666154-a77d4c15-0b82-4c19-a543-44ee23b62162.png">


### Describe Linked Lists

- a LinkedList is a type of dynamic array. The list increases if we add/remove items. Elements are not stored continuously, there is no need to increase the size. LinkedList is implemented using the doubly linked list data structure. Between a normal linked list and a doubly LinkedList is that a doubly linked list contains an extra pointer, typically called the previous pointer, together with the next pointer and data which are there in the singly linked list.


### Describe Java Generic T
- parameterized types allows for (Integer, String, … etc., and user-defined types) to be a parameter to methods, classes, and interfaces. it is possible to create classes that work with different data types. An entity such as class, interface, or method that operates on a parameterized type is a generic entity.
- Object is a superclass of all other classes, and Object reference points to other objects. These features lack type safety. Generics add are safer as they have reference points which is a great safety feature.  Generics in Java are similar to templates in C++. For example, classes like HashSet, ArrayList, HashMap, etc., use generics very well. There are some fundamental differences between the two approaches to generic types. sus


### Queue Add and Delete
- The Queue interface in the java.util package extends the interface o Collection is used to hold elements processed in FIFO(First In First Out) order. It is an ordered list of objects with its use limited to insert elements at the end of the list and deleting elements from the start of the list, (i.e.), it follows the FIFO or the First-In-First-Out principle.

- remove() of Interface (queue) returns and removes the element in the container at the front. It deletes the head of the container. The method throws an NoSuchElementException when the Queue is empty. amogus


To add an element in a queue, we can use the add() method. The insertion order is not kept in the PriorityQueue. The elements are stored based on the priority order which is ascending by default.



### Merge 2 Queues
 - In order to merge 2 queues there is a list of steps you must go through:
1. Make pointers for both of the queues.
2. Make another queue, add the node having least value from the other two queues(the pointer's node having the smallest value) to it and move that pointer to the next node.
3. Again compare the node's values and add the node having the smallest value to the queue and move that pointer to the next node.
4. Keep doing this until rear of both the queues are reached.
bear



### Reversing a Queue
- Reersing the queue is simply reinserting the data in an inverse order. So now our task is to choose such data-structure which can serve the purpose. According to the approach, the data-structure should have the property of ‘LIFO’ as the last element to be inserted in the data structure should actually be the first element of the reversed queue. The stack could help in approaching this problem. This will be a two-step process:
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

- Here's an example of some functions above at work: deer


