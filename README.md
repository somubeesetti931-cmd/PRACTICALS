  # PRACTICAL-1

## Summary

In this practical, different sorting techniques such as **Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort** were implemented and analyzed. Their execution times and time complexities were compared to understand their performance. Bubble Sort, Selection Sort, and Insertion Sort generally take **O(n²)** time, while Merge Sort and Quick Sort are more efficient for larger datasets. Merge Sort has **O(n log n)** time complexity in all cases, whereas Quick Sort provides **O(n log n)** average performance but may take **O(n²)** in the worst case.

## Conclusion

The practical demonstrates that sorting algorithms differ significantly in their performance. Simple algorithms such as Bubble, Selection, and Insertion Sort are suitable for smaller datasets, while Merge Sort and Quick Sort are better choices for larger datasets. The comparison helps in selecting an appropriate sorting technique based on the size and requirements of the data.

  

  
# PRACTICAL-2

## Summary

In this practical, **Linear Search and Binary Search** algorithms were implemented and compared based on their performance. Linear Search checks the elements sequentially until the required element is found, giving it a time complexity of **O(n)**. Binary Search repeatedly divides the sorted data into two parts and searches only the required portion, resulting in a time complexity of **O(log n)**. However, Binary Search can only be applied when the data is sorted.

## Conclusion

Both searching techniques successfully locate the required element in a dataset. Linear Search is simple and can be used with sorted or unsorted data, while Binary Search provides much faster searching for large sorted datasets. Therefore, Binary Search is preferred when the data is sorted and performance is important, whereas Linear Search is useful for smaller or unsorted collections.

 

# PRACTICAL-3

## Summary

In this practical, the **Max-Heap Sort** algorithm was implemented using the Max Heap data structure. The algorithm first converts the given elements into a Max Heap, where the largest element is placed at the root. The largest element is then moved to its correct position by swapping it with the last element, followed by readjusting the heap. This process continues until all elements are sorted in ascending order. Heap Sort provides **O(n log n)** time complexity.

## Conclusion

The Max-Heap Sort algorithm successfully sorts the given elements using the properties of a Max Heap. It provides consistent **O(n log n)** performance and does not require additional arrays for sorting. Therefore, Heap Sort is an efficient and reliable sorting technique, especially when consistent performance and memory usage are important.



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


