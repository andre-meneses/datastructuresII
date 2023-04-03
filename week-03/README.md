## Week 03
A series of interview-like questions were solved with the help of chatgpt.
 - [Jupyter Notebook](./Code_Interview_Linked_Queue_Stacks.ipynb)
 - [Loom video](https://www.loom.com/share/47be2f73f0014146827e6eb31f8de4eb)

### Problem 1
> Write a function that in a non-empty array of distinct integers and an integer representing a target sum. If any two numbers in the input array sum up to the target sum, the function should return then in an array, in any order. If no two numbers sum up to the target sum, the function should return an empty array.
>
> Note that the target sum has to be obtained by summing two different integers in the array; you can't add a single integer to itself in order to obtain the target sum.
>
> You can assume that there will be at most one pair of numbers summing up to the target sum 

Given a target sum x, the proposed solution  computes 'targetSum - x' and verifies whether the found value is in a dictionary 'numbers'. The entry is only added to the dictionary after the verification, that ensures that the complement cannot be the number itself. Only one pass through the list is necessary, and the verification step is constant in time. Hence, the function is O(n) in time and space.

### Problem 2
>  You're given the head of a doubly Linked List whose nodes are in sorted order with respect to their values. Write a function that returns a modified version of the Linked List that doesn't contain any node with duplicate values. The Linked List should be modified in place (i.e, you shouldn't create a brand new list), and the modified Linked List should still have its nodes sorted with respect to their values.
> 
A simple pointer manipulation problem. If two nodes are equal, point to the next non-equal node. 

### Problem 3
> Write a function that takes two doubly linked lists that are in sorted order, respectively. The function should merge the lists in place (i.e., it shouldn't create a brand new list) and return the head of the merged list; the merged list should be in sorted order.

The function works by verifying when the nodes of the linked lists are out of order and by using pointer manipulation to merge the nodes. At the end, the head and tail are reorganized and any remaing nodes are connected. 

### Problem 4
 > Given an array of buildings and a direction that all of the buildings face, return an array of the indices of the buildings that can see the sunset.
 > A building can see the sunset if its strictly taller than all of the buildings that come after it in the direction that it faces. 
 >
 > The input array named ``buildings`` contains positive, non-zero integers representing the heights of the buildings. A building at index ``i`` thus has a height denoted by ``buildings[1]``. All of the buildings face the same direction, and this direction is either east or west, denoted by the input string named ``direction``, which will always be equal to either ``EAST`` or ``WEST``. In relation to the input array, you can interpret these directions as right for east and left for west. 
 >
 > Important note: the indices in the ouput array should be sorted in ascending order. 

