---
title: Linked Lists
---

## Linked Lists

This is a stub. [Help our community expand it](https://github.com/freeCodeCamp/guide-articles/tree/master/articles/Computer-Science/Data-Structures/Linked-Lists/index.md).

[This quick style guide will help ensure your pull request gets accepted](https://github.com/freeCodeCamp/guide-articles/blob/master/README.md).

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->

What is a Linked list?
It is a collection of nodes, where node is an entity which contains certain data and the address to the next node.
The nodes are linked sequentially, with each node pointing to the address of the next node and so on till the last node contains NULL in the address field .
The structure of a node is
struct node{
    int data;
    struct node *next; //next is address of next node
 };
 
Advantages of Linked Lists

They are a dynamic in nature which allocates the memory when required.
->Insertion and deletion operations can be easily implemented.
->Stacks and queues can be easily executed.
->Linked List reduces the access time.

Disadvantages of Linked Lists
->The memory is wasted as pointers require extra memory for storage.
->No element can be accessed randomly; it has to access each node sequentially.
->Reverse Traversing is difficult in linked list.

Applications of Linked Lists
->Linked lists are the basic data structures used to implement stacks, queues, graphs, etc.
->Linked lists let you insert elements at the beginning and end of the list.
->Unlike arrays, In Linked Lists we don't need to know the size in advance.
