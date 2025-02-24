Download link :https://programming.engineering/product/heap-in-class-practice/


# Heap-In-Class-Practice
Heap – In-Class Practice
Create a class named MinHeap in a file named MinHeap.h
The MinHeap class should have the following in the private field:
A string pointer to a dynamically allocated array called heap.
An int called sz for size.
An int called capacity for the max size of the heap.
A helper function called parent that takes an int i and returns the parent node index of the current child index.
A helper function called left that takes an int i and returns the left child index given the parents index.
A helper function called right that takes an int i and returns the right child index given the parents index.
A void function that resizes the heap.
The MinHeap class should have the following in the public field:
A constructor that takes an int c for the starting capacity. It should set the capacity to what is passed in, sz to 0, and initialize heap.
A destructor that will delete the dynamically allocated array.
A void insert method that takes a string and inserts it into the heap using the string length for comparison such that the smallest string will be the root.
A remove method that returns root and reheaps the heap using the length of the strings.*
A isEmpty method that returns a bool: True if sz = 0 and false if sz != 0.
A getSize method that returns sz.
A getHeight method that uses the ceil and log2 functions from the cmath library to return the height of the heap.
A peek method that returns the value at the root of the heap but does not remove it.*
A clear method that deletes the old heap and resets the size to 0.
*if sz is 0, return the empty string: “”
Now create a driver file called Driver.cpp that does the following:
Dynamically allocate a new MinHeap with initial size 4 called heap.
Then insert:
everyday
do
