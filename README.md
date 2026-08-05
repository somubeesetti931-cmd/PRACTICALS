  PRATICAL-1  
  
  The implementation and time analysis of Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort show that different sorting algorithms have different efficiencies. Bubble Sort, Selection Sort, and Insertion Sort are simple to implement but become slow for large datasets because their average and worst-case time complexity is O(n²). Merge Sort and Quick Sort are more efficient for large datasets. Merge Sort guarantees O(n log n) time in all cases but requires extra memory, while Quick Sort has an average time complexity of O(n log n) and is usually the fastest in practice, although its worst case is O(n²). Therefore, Merge Sort and Quick Sort are preferred for handling large amounts of data.

  
 PRATICAL-2

 
 The implementation and time analysis of Linear Search and Binary Search show that Binary Search is much more efficient than Linear Search for large datasets. Linear Search checks each element one by one and works on both sorted and unsorted arrays, but its time complexity is O(n). Binary Search repeatedly divides the search space into two halves, making it much faster with a time complexity of O(log n), but it requires the data to be sorted. Therefore, for small or unsorted data, Linear Search is suitable, while for large sorted data, Binary Search is the better and more efficient choice.


  PRATICAL-3

  The Max-Heap Sort algorithm is an efficient comparison-based sorting algorithm that uses a Max Heap data structure to sort elements in ascending order. It first builds a Max Heap from the given array and then repeatedly swaps the root (largest element) with the last element, reducing the heap size each time until the array is completely sorted. Heap Sort provides consistent performance and is suitable for sorting large datasets.
