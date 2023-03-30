## Week 03

A series of interview-like questions were solved with the help of chatgpt. 

### Problem 1
> "Write a function that in a non-empty array of distinct integers and an integer representing a target sum. If any two numbers in the input array sum up to the target sum, the function should return then in an array, in any order. If no two numbers sum up to the target sum, the function should return an empty array.
>
> Note that the target sum has to be obtained by summing two different integers in the array; you can't add a single integer to itself in order to obtain the target sum.
>
> You can assume that there will be at most one pair of numbers summing up to the target sum "

Given a target sum x, the proposed solution function computes 'targetSum - x' and verifies whether the found value is in a dictionary 'numbers'. The entry is only added to the dictionary after the verification, that ensures that the complement cannot be the number itself. Only one pass through the list is necessary, and the verification step is constant in time. Hence, the proposed solution is O(n) in time and O(n) in space.

### Problem 2

### Problem 3

### Problem 4
