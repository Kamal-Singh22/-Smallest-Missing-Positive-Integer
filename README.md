# -Smallest-Missing-Positive-Integer
Given an unsorted integer array nums, return the smallest missing positive integer.
Explanation:
Cyclic Sort: The algorithm places each number at its correct index if it is in range [1, n].
Identify Missing Positive: The first index where nums[i] != i+1 gives the smallest missing positive number.
Return n + 1: If all numbers are in place, the missing number is n + 1.
Time Complexity:
O(n) for swapping elements to their correct positions.
O(n) for checking the missing number.
Overall Complexity: O(n)...
