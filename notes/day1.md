## Day 1: Two Sum

Solved the Two Sum problem using the HashMap approach.

### Understanding
The goal is to find two indices whose values add up to the target.  
A brute-force solution checks all possible pairs, but that takes O(n²) time.

The optimized approach uses a HashMap to store previously visited numbers and their indices.  
For each element, we calculate the complement using:

target - currentNumber

If the complement is already present in the HashMap, we return the index of the complement and the current index.  
Otherwise, we store the current number and its index in the map.

### Complexity
Time Complexity: O(n)  
Space Complexity: O(n)

### Key Learning
HashMap helps reduce repeated searching by allowing average O(1) lookup for previously seen elements.