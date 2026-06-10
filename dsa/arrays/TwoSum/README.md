## Problem 1: Two Sum

### Problem Link
https://leetcode.com/problems/two-sum/

### Pattern
Array + HashMap

### Brute Force Approach
Check every pair and return the indices when the sum equals the target.

### Optimized Approach
Use a HashMap to store previously seen numbers and their indices.  
For each number, check if its complement exists in the map.

### Time Complexity
- Brute Force: O(n²)
- Optimized: O(n)

### Space Complexity
- Brute Force: O(1)
- Optimized: O(n)

### Edge Cases
- Duplicate numbers
- Negative numbers
- Zero values
- Pair appearing at the end