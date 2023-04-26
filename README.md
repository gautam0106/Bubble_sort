# Bubble_sort

Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order.

# Working of Bubble Sort
Suppose we are trying to sort the elements in ascending order.

First Iteration (Compare and Swap)
Starting from the first index, compare the first and the second elements.

If the first element is greater than the second element, they are swapped.

Now, compare the second and the third elements. Swap them if they are not in order.

The above process goes on until the last element.

Remaining Iteration The Bubble Sort is an efficient sorting algorithm that works in O(n log n) time, where n is the number of items to be sorted. The first iteration of the Bubble Sort sorts the input item at index 0 into ascending order, and then repeats this process until all the inputs have been sorted. So, after performing one iteration of the bubble sort on an input dataset containing five items, there would be four remaining iterations left to perform.
The Bubble Sort Algorithm
The basic bubble sort algorithm can be explained as follows:

bubbleSort(array)

for i <- 1 to indexOfLastUnsortedElement-1

if leftElement > rightElement

  swap leftElement and rightElement
end bubbleSort

This algorithm does the swapping of elements to get the final output in the desired order. For instance, if you pass an array consisting of the elements: (6, 3, 8, 2, 5, 7), the final array after the bubble sort implementation will be: (2, 3, 5, 6, 7, 8).

# Output
<img width="676" alt="image" src="https://user-images.githubusercontent.com/113123292/234487618-a511fa93-0d87-449d-a65a-895c3da1354d.png">
