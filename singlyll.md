***Program to create and display a singly linked list***

**Explanation**

In this program, we need to create a singly linked list and display all the nodes present in the list.

**Singly Linked List**

The singly linked list is a linear data structure in which each element of the list contains a pointer which points to the next element in the list. Each element in the singly linked list is called a node. Each node has two components: data and a pointer next which points to the next node in the list. The first node of the list is called as head, and the last node of the list is called a tail. The last node of the list contains a pointer to the null. Each node in the list can be accessed linearly by traversing through the list from head to tail.
Program to create and display a singly linked list

Consider the above example; node 1 is the head of the list and node 4 is the tail of the list. Each node is connected in such a way that node 1 is pointing to node 2 which in turn pointing to node 3. Node 3 is again pointing to node 4. Node 4 is pointing to null as it is the last node of the list.

**Algorithm**

   1. Create a class Node which has two attributes: data and next. Next is a pointer to the next node.
   2. Create another class which has two attributes: head and tail.
   3. addNode() will add a new node to the list:
       
       a.Create a new node.
       
       b.It first checks, whether the head is equal to null which means the list is empty.
       
       c.If the list is empty, both head and tail will point to the newly added node.
       
       d,If the list is not empty, the new node will be added to end of the list such that tail's next will point to the newly added                node.This new node will become the new tail of the list.
    
   
   4.display() will display the nodes present in the list:
    
     a.Define a node current which initially points to the head of the list.
      
     b.Traverse through the list till current points to null.
      
     c.Display each node by making current to point to node next to it in each iteration.
