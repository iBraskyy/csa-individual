{% include navigation.html %}

## Review tickets

[Week 0](https://github.com/shekark642/M221p2-roopies/issues/28)

[Week 1](https://github.com/shekark642/M221p2-roopies/issues/37)

[Week 2](https://github.com/shekark642/M221p2-roopies/issues/41)

[Week 3](https://github.com/shekark642/M221p2-roopies/issues/49)

[Final](https://github.com/shekark642/M221p2-roopies/issues/51)


### Sorts

#### Bubble Sort

<img width="495" alt="Screen Shot 2022-04-16 at 4 20 26 PM" src="https://user-images.githubusercontent.com/72888867/163694071-be41e3cb-2ec3-436d-ba3e-62fef3f370a4.png">

The Bubble sort functions by analyzing two adjacent pairs of objects in array.

#### Insertion Sort

<img width="358" alt="Screen Shot 2022-04-16 at 4 28 00 PM" src="https://user-images.githubusercontent.com/72888867/163694194-679c04a3-45f5-4b30-b1fd-682cfcc9c5e8.png">

Insertion sort is much simpler and builds sorted array one item at a time

#### Merge Sort

<img width="586" alt="Screen Shot 2022-04-16 at 4 28 38 PM" src="https://user-images.githubusercontent.com/72888867/163694203-8d3af1a3-bd56-4d5d-9860-e5bb44900bd7.png">

#### Selection Sort

<img width="468" alt="Screen Shot 2022-04-16 at 4 28 58 PM" src="https://user-images.githubusercontent.com/72888867/163694208-55c320cc-7c1b-4df7-9968-8279acde0394.png">

Seleciton sort sorts an array by finding minimum element from the unsorted part and then puts it at the very beginning.



### Calculator

Linked lists is a data strucutre where each data value has a link that connects to the NEXT piece of data. There are nodes that are connected to the current node, either next or previous. Genertic T was implemented because we weren't able to know which data types would be inserted into the queue, so it gives us the abiity to use data without specifying which type. 




   We used stacks in order to implement Reverse Polish Notation to create the calculator object.
   
   
   Here is the first part to my code. This is setting up the transfer between RPN and our final product. We stack which holds our values as we "dissect" RPN. 
   
 <img width="449" alt="Screen Shot 2022-03-30 at 9 46 38 AM" src="https://user-images.githubusercontent.com/72888867/160888357-5aa6304a-fe35-498c-92fc-89e99f8aee78.png">

   
   Here are the calculation steps
   <img width="415" alt="Screen Shot 2022-03-30 at 9 46 50 AM" src="https://user-images.githubusercontent.com/72888867/160888392-c77446dd-143c-499d-8f27-22bda22db32f.png">
   
   
   Lastly here are the values being popped and also the tostring method which prints our final product as we want it.

   <img width="601" alt="Screen Shot 2022-03-30 at 9 47 07 AM" src="https://user-images.githubusercontent.com/72888867/160888448-beaee9e9-6521-47fb-8030-7df9032a7795.png">

   
 creating the argument constructor which will be expecting a mathematical expression
   


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


