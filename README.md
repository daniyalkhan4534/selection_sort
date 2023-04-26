# selection_sort

The smallest (or largest) element from the unsorted part of the list is regularly chosen and moved to the sorted part of the list using the straightforward and effective sorting algorithm known as selection sort. The algorithm repeatedly chooses the smallest (or largest) element from the list's unsorted section and switches it with the unsorted section's initial member. Up until the complete list is sorted, this procedure is repeated for the last unsorted section of the list. A selection sort variant known as "Bidirectional selection sort" alternates between the smallest and largest elements in the list of elements, which can sometimes make the algorithm run more quickly.

![image](https://user-images.githubusercontent.com/127819492/234484011-2be43256-4a3b-4cac-b2cc-cafaa22b6a21.png)

The algorithm maintains two subarrays in a given array.

The subarray which already sorted.
The remaining subarray was unsorted.
In every iteration of the selection sort, the minimum element (considering ascending order) from the unsorted subarray is picked and moved to the beginning of the sorted subarray.

After every iteration sorted subarray size increase by one and the unsorted subarray size decrease by one.
After the N (size of the array) iteration, we will get a sorted array.


Steps to solve the problem are:
1.Initialize minimum value(min_idx) to location 0.
2.Traverse the array to find the minimum element in the array.
3.While traversing if any element smaller than min_idx is found then swap both values.
4.Then, increment min_idx to point to the next element.
5.Repeat until the array is sorted.
