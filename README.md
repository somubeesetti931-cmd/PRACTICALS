  PRATICAL-1  
  
  The implementation and time analysis of Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort show that different sorting algorithms have different efficiencies. Bubble Sort, Selection Sort, and Insertion Sort are simple to implement but become slow for large datasets because their average and worst-case time complexity is O(n²). Merge Sort and Quick Sort are more efficient for large datasets. Merge Sort guarantees O(n log n) time in all cases but requires extra memory, while Quick Sort has an average time complexity of O(n log n) and is usually the fastest in practice, although its worst case is O(n²). Therefore, Merge Sort and Quick Sort are preferred for handling large amounts of data.

  
 PRATICAL-2

 
 The implementation and time analysis of Linear Search and Binary Search show that Binary Search is much more efficient than Linear Search for large datasets. Linear Search checks each element one by one and works on both sorted and unsorted arrays, but its time complexity is O(n). Binary Search repeatedly divides the search space into two halves, making it much faster with a time complexity of O(log n), but it requires the data to be sorted. Therefore, for small or unsorted data, Linear Search is suitable, while for large sorted data, Binary Search is the better and more efficient choice.


  PRATICAL-3

  The Max-Heap Sort algorithm is an efficient comparison-based sorting algorithm that uses a Max Heap data structure to sort elements in ascending order. It first builds a Max Heap from the given array and then repeatedly swaps the root (largest element) with the last element, reducing the heap size each time until the array is completely sorted. Heap Sort provides consistent performance and is suitable for sorting large datasets.


  # PRACTICAL-4

## Summary

In this practical, the factorial of a number was calculated using two different approaches: **iteration and recursion**. The user provides a number as input, and both methods are used to find its factorial. The execution time of each approach is calculated using Python’s `time.perf_counter()` function. The iterative approach uses a loop to perform the calculation, whereas the recursive approach calls the same function repeatedly until the base condition is satisfied.

## Conclusion

Both approaches successfully produce the factorial of the given number. The time complexity of both iterative and recursive methods is **O(n)**. However, their space complexities are different. The iterative method requires **O(1)** extra space, while the recursive method requires **O(n)** space due to the recursive function calls stored in the call stack. Hence, iteration is more efficient in terms of memory, while recursion offers a straightforward and logical way to implement factorial calculation.


# PRACTICAL-7

## Summary

This practical demonstrates the **Coin Change problem** using the Dynamic Programming approach. The objective is to determine the minimum number of coins needed to form a specified amount. Dynamic Programming maintains a table of previously computed values and reuses them whenever required. This prevents the same subproblems from being calculated multiple times. The algorithm requires **O(n × A)** time and **O(A)** additional space.

## Conclusion

The Dynamic Programming technique provides an effective way to solve the minimum coin change problem. By saving the results of smaller subproblems, it avoids unnecessary repeated calculations and improves the overall efficiency of the program. The method successfully determines the minimum number of coins required for the target amount and performs significantly better than a basic recursive solution for larger inputs.


