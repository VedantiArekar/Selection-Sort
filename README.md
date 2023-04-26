# Selection-Sort

Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted. One variation of selection sort is called “Bidirectional selection sort” which goes through the list of elements by alternating between the smallest and largest element, this way the algorithm can be faster in some cases.

![image](https://user-images.githubusercontent.com/125825670/234365996-24bc866a-eaca-4c43-b0c0-3f9f9af96e0e.png)

Summary:

1. Selection sort is a simple and easy-to-understand sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. 

2. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted.

3. It has a time complexity of O(n^2) in the worst and average case which makes it less efficient for large data sets.

4. Selection sort is a stable sorting algorithm.

5. It can be used to sort different types of data.

6. It has specific applications where it is useful such as small data sets and memory-constrained systems.

The algorithm maintains two subarrays in a given array.

a. The subarray which already sorted.

b. The remaining subarray was unsorted.

In every iteration of the selection sort, the minimum element (considering ascending order) from the unsorted subarray is picked and moved to the beginning of the sorted subarray. 

After every iteration sorted subarray size increase by one and the unsorted subarray size decrease by one.

After the N (size of the array) iteration, we will get a sorted array.
