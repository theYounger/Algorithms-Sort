Create a README.md file and for each algorithm include the following:

-Explain to a five year old how the algorithm works (3-4 sentences max)
-Psuedo code for each sorting implementation
-In your own words, describe the performance of the alogirthm for the following cases:
--Best case scenario
--Worst case scenario
_______________________________________________________________________________________

===============BUBBLE SORT===================

Description: A sorting algorithm that orders numbers according to their size. It steps through an array of numbers, comparing each number to the next one in line to check which one is bigger. If the current element is smaller than the next one in line, the two elements remain where they are. If the current element is bigger than the next one in line, the two elements swap positions. Bubble Sort repeatedly passes over the array until the final pass detects that swaps are no longer occurring.

Best case scenario:
The given array is already in order. Bubble Sort is unique from other sorting algorithms in that it checks for disorder before each pass. Bubble Sort passes over the ordered array once, detects no swaps, and then returns us the array. This has a big-O complexity of O(n).

Worst case scenario:
The given array is inversely ordered. For example, if the best case is [1,2,3,4,5], then the worst case is [5,4,3,2,1]. Bubble Sort will have to make the maximum possible passes to sort an inversely ordered array. This is indicated by a big-O complexity of O(n^2).

===============QUICK SORT===================


