# Chapter 1
* inserion sort O(n*n)
* merge sort O(n log n)
if a faster computer(A) running insertion sort against a slower computer(B) running merge sort both 
sort an array of 10 million numbers and A is 1000 times faster than computer B in raw computing power
if you wrote code of insertion sort in machine language for computer A, and the resulting code
requires 2(n^2) instructions to sort n numbers
And merge sort, using a high-level language with an inefficient
compiler, with the resulting code taking 50(n log n) instructions
A takes 20,000 seconds (more than 5.5 hours)
B takes 1163 seconds (less than 20 minutes)
### as the problem size increases, so does the relative advantage of merge sort