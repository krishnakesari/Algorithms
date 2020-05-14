# Algorithms

Algorithms powers softwares and provide blue print on how a task need to be done.

Algortihm complexity
1. Space complexity
2. Time complexity

Algorithm classification
1. Serial/Parallel
2. exact/approximate
3. deterministic (guesses) /non-deterministic

Algortihm Performance
Big-O notation - O denotes order of operation 

O(1) - Constant time - Looking up for a simple element in an array
O(log n) - Logarithmic - Finding an item in a sorted array with a binary search
O(n) - Linear time - Searching an unsorted array for a specifc value
O(n log n) - Log linear - Complex sorting algorithms like heap sort and merge sort
O(n2) - Quadratic - Simple sorting algorithms, such as bubble sort, selection sort, and insertion sort

## Data Structures

Organizing information in efficient way 

Arrays
1. Collection of elements identified by index or key 
2. Array starts with position '0'
3. Two dimensional array will have 2 indexes eg: [2,1]
4. Insert or delete item at begining or in middle happens in linear time O(n)
5. Insert or delete item at end will happen in Constant time O(1)

Linked lists

Linear collection of data elements, called nodes
1. Contains reference to the next node in the list
2. If no link, that is end of list
3. double linked list - has information on two neighboring lists
4. elements can be easily and quickly inserted and removed
5. Can't do constant time O(1) random item access like array 
6. Item look up happens in Linear time 

Stacks and Queues

Stack is the collection of elements - push and pop operations
1. last item pushed is the first one popped 
2. Constant time operation 

Usage:
1. Expression Processing
2. Back tracking: browser history organization is stacked

Queue supports adding and removing items
1. First item added is the first item out
2. Constant time operation

Usage:
1. Order processing
2. Messaging - sending messages out in an order based on queue


Hash Tables
Associative arrays - maps keys to associative values 
1. Key to value mappings are unique
2. Hash tables are typically very fast
3. Hash tables don't order entries in a predictable way - data spread out randomly in memory

## Recursion
Function calls itself 
1. Recursion fuction need to have a breaking condition
2. Each time function is called, old arguements are saved


## Sorting Data
Placing data in an specific order

1. Bubble sort 
a. Begins by comparing swaps value if first one is larger - so largest value move to end ! 
b. Quadratic time complexity - for loop inside a for loop
c. not a practical option 

2. Merge sort - uses recursion to implement logic
a. Divide and conquer algorithm
b. Breaks dataset into individual pieces 
c. merge two sorted arrays together, through advancing towards small to large numbers 

3. quick sort - uses recursion to implement logic 
a. Divide and conquer algorithm
b. Operates in place of the data
c. Pivot point selection - pick a pivot position as 1st position is called pivot value
    i. All the work is done in partition stage
    ii. value larger than pivot value and shuffle values


## Searching Data
Finding a specific data in a structure (searching a string)
## Other Alogrithms

## Computational Algorithms
Given one input, calculating another 

## Collection Algorithms
Works with collection of data (counting data, subsetting/filtering, navigating among elements)

