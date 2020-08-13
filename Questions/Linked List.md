# List of questions

### Find a Node in Linked List

You have been given a singly linked list of integers. Write a function that returns the index/position of an integer data denoted by 'N' (if it exists). Return -1 otherwise.

*Note : Assume that the Indexing for the singly linked list always starts from 0.* 

Sample Input 

```
3 4 5 2 6 1 9 -1

5

10 20 30 40 50 60 70 -1

6
```

Sample Output

```
2
-1
```

### AppendLastNToFirst

You have been given a singly linked list of integers along with an integer 'N'. Write a function to append the last 'N' nodes towards the front of the singly linked list and returns the new head to the list.

*Note While specifying the list elements for input, -1 indicates the end of the singly linked list and hence, would never be a list element.*

Sample Input 

```
1 2 3 4 5 -1
3
10 20 30 40 50 60 -1
5
```

Sample Output

```
3 4 5 1 2
20 30 40 50 60 10
```

###  Eliminate duplicates from LL

You have been given a singly linked list of integers where the elements are sorted in ascending order. Write a function that removes the consecutive duplicate values such that the given list only contains unique elements and returns the head to the updated list.

Sample Input 

```
1 2 3 3 4 3 4 5 4 5 5 7 -1
```

Sample Output

```
1 2 3 4 3 4 5 4 5 7 
```

###  Print Reverse LinkedList

You have been given a singly linked list of integers. Write a function to print the list in a reverse order.
To explain it further, you need to start printing the data from the tail and move towards the head of the list, printing the head data at the end.

Sample Input 

```
1 2 3 4 5 -1
```

Sample Output

```
5 4 3 2 1
```

### Palindrome LinkedList

You have been given a head to a singly linked list of integers. Write a function check to whether the list given is a 'Palindrome' or not.

Sample Input 

```
9 2 3 3 2 9 -1
```

Sample Output

```
true
```	

### Even after Odd LinkedList


Arrange elements in a given Linked List such that, all even numbers are placed after odd numbers. Respective order of elements should remain same.

*Note: Input and Output has already managed for you. You don't need to print the elements, instead return the head of updated LL.*

Sample Input 

```
1 4 5 2 -1
```

Sample Output

```
1 5 4 2
```	

### Delete every N nodes


Given a linked list and two integers M and N. Traverse the linked list such that you retain M nodes then delete next N nodes, continue the same until end of the linked list. That is, in the given linked list you need to delete N nodes after every M nodes.

Sample Input 

```
1 2 3 4 5 6 7 8 -1
2
2
```

Sample Output

```
1 2 5 6
```	

### Swap two Node of LL


Given a linked list, i & j, swap the nodes that are present at i & j position in the LL. You need to swap the entire nodes, not just the data.

Sample Input 

```
3 4 5 2 6 1 9 -1
3 4
```

Sample Output

```
3 4 5 6 2 1 9
```	

### kReverse 

Implement kReverse( int k ) in a linked list i.e. you need to reverse first K elements then reverse next k elements and join the linked list and so on.

*Note You don't need to print the elements, just return the head of updated LL.*

Sample Input 

```
1 2 3 4 5 6 7 8 9 10 -1
4
```

Sample Output

```
4 3 2 1 8 7 6 5 10 9
```	

###  Bubble Sort (Iterative) LinkedList

Sort a given linked list using Bubble Sort (iteratively). While sorting, you need to swap the entire nodes, not just the data.

Sample Input 

```
1 4 5 2 -1
```

Sample Output

```
1 2 4 5
```	

### Leetcode Questions

1. [Reverse Linked List II](https://leetcode.com/problems/reverse-linked-list-ii/)

2. [Odd Even Linked List](https://leetcode.com/problems/odd-even-linked-list/)

3. [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)

4. [Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/)

5. [Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)

6. [Design Linked List](https://leetcode.com/problems/design-linked-list/)