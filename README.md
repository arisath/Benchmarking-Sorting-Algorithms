# Benchmarking Sorting Algorithms
Benchmarking the performance of different sorting algorithms implemented in Java

The following sorting algorithms are included in the class Benchmarking:

| Algorithm | Best Case | Average Case | Worst Case | 
| --------- | --------- | -----------  | ---------- | 
| **bubblesort** | O(n) | O(n²) |O(n²) | 
| **selectionsort** | O(n^2) | O(n²) | O(n²) | 
| **insertionsort** | O(n) | O(n²) | O(n²) |
| **quicksort** | O(n log(n)) | O(n log(n)) | O(n²) |
| **mergesort** | O(n log(n)) | O(n log(n)) | O(n log(n)) |


The following metrics have been conducted on a 2.4 GHz Intel Core i7:

| Algorithm | 10000 Entries | 100000 Entries | 1000000 Entries |
| --------- | --------- | ----------- | ---------- | 
| bubblesort | 241 ms | 29.2 s | 48.5 mins | 
| selectionsort | 33 ms | 1.9 s | 2.9 mins | 
| insertionsort | 1 ms | 4 ms | 12 ms |
| quicksort | 2 ms | 23 ms | 34 ms |
| mergesort | 5 ms | 26 ms | 137 ms |
