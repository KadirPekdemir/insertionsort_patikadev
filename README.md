# insertionsort_patikadev
[22,27,16,2,18,6] -> Insertion Sort

1. Write the stages of the above sequence according to the sort type. 

        [2,27,16,22,18,6] 
        [2,6,16,22,18,27] 
        [2,6,16,22,18,27]
        [2,6,16,18,22,27] 
        [2,6,16,18,22,27] 

2. Write the Big-O notation.
n*(n+1)/2=(n^2+n)/2   ->  O(n^2)

3. Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we
are looking for is at the end, Best case: The number we are looking for is at the beginning of the series.

What case does the number 18 fall into after the array is sorted? Write. Since the number of Time Complexity 18 is in the
middle after the sorting it is included in the Average case.

4. Write the first 4 steps of [7,3,5,8,2,9,4,15,6] according to Insertion Sort.
        [2,3,5,8,7,9,4,15,6]
        [2,3,5,8,7,9,4,15,6]
        [2,3,4,8,7,9,5,15,6]
        [2,3,4,5,7,9,8,15,6]
