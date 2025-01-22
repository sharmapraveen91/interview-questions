# DSA Interview Questions

## 1. **Recursion**

1. **Solve the N-th Fibonacci number using recursion.**
   - **Explanation:** Recursion is a natural fit for solving Fibonacci numbers as it follows the recurrence relation: `F(n) = F(n-1) + F(n-2)`.
   
2. **Solve the Tower of Hanoi problem.**
   - **Explanation:** This problem involves moving disks from one peg to another, following the rules of recursion.
   
3. **Find the maximum depth of a binary tree using recursion.**
   - **Explanation:** Use recursion to explore each node and determine the maximum depth of the tree.

4. **Generate all subsets of a set (Power set).**
   - **Explanation:** Use recursion to generate all subsets of a given set by either including or excluding each element.

5. **Solve the "sum of digits" problem using recursion.**
   - **Explanation:** Implement a function to find the sum of digits of a given number using recursion.

---

## 2. **Dynamic Programming**

1. **Solve the 0/1 Knapsack Problem.**
   - **Explanation:** Given weights and values, find the maximum value that can be obtained with a given capacity using dynamic programming.

2. **Find the longest common subsequence (LCS) between two strings.**
   - **Explanation:** Use dynamic programming to build a solution by comparing characters of the two strings and finding the longest subsequence.

3. **Solve the Coin Change problem.**
   - **Explanation:** Given a set of coin denominations and a target value, find the minimum number of coins required to make the target value.

4. **Find the maximum sum of non-adjacent elements in an array.**
   - **Explanation:** Use dynamic programming to solve the problem by maintaining two states: one including the current element and one excluding it.

5. **Solve the Longest Increasing Subsequence (LIS) problem.**
   - **Explanation:** Use dynamic programming to find the longest subsequence of a given array where the elements are strictly increasing.

---

## 3. **Greedy Algorithms**

1. **Activity Selection Problem (Maximum number of activities).**
   - **Explanation:** Given start and finish times of activities, select the maximum number of activities that can be performed by a single person.

2. **Huffman Coding.**
   - **Explanation:** This problem involves encoding a set of characters using a greedy approach based on their frequencies.

3. **Fractional Knapsack Problem.**
   - **Explanation:** Unlike the 0/1 knapsack problem, in the fractional knapsack, you can take fractions of an item. Solve it using a greedy strategy based on value-to-weight ratio.

4. **Find the minimum number of coins required to make a change (using denominations).**
   - **Explanation:** Given an amount and a set of coin denominations, use a greedy approach to find the minimum number of coins needed to make that amount.

5. **Job Scheduling Problem with deadlines.**
   - **Explanation:** Given a set of jobs with deadlines and profits, find the maximum profit you can achieve by scheduling the jobs optimally using a greedy approach.

---

## 4. **Backtracking**

1. **Solve the N-Queens problem.**
   - **Explanation:** Place `N` queens on an `N x N` chessboard such that no two queens threaten each other. Solve using backtracking.

2. **Solve the Sudoku puzzle.**
   - **Explanation:** Use backtracking to fill a partially filled 9x9 grid following the Sudoku rules.

3. **Generate all permutations of a string.**
   - **Explanation:** Use backtracking to generate all possible permutations of a given string.

4. **Solve the subset sum problem.**
   - **Explanation:** Given a set of numbers and a target sum, determine if there exists a subset of numbers that sum to the target value using backtracking.

5. **Solve the Rat in a Maze problem.**
   - **Explanation:** Given a maze, find a path from the top-left corner to the bottom-right corner using backtracking.

---

## 5. **Divide and Conquer**

1. **Merge Sort Algorithm.**
   - **Explanation:** Divide the array into halves, recursively sort each half, and then merge the sorted halves.

2. **Quick Sort Algorithm.**
   - **Explanation:** Use the divide-and-conquer technique to sort an array by selecting a pivot and partitioning the array around the pivot.

3. **Binary Search.**
   - **Explanation:** Perform binary search on a sorted array by dividing the search space in half at each step.

4. **Finding the Median of Two Sorted Arrays.**
   - **Explanation:** Find the median of two sorted arrays using divide-and-conquer.

5. **Count the number of inversions in an array.**
   - **Explanation:** Use merge sort to count the number of inversions in an array efficiently.

---

## 6. **Graph Algorithms**

1. **Depth First Search (DFS) and Breadth First Search (BFS).**
   - **Explanation:** Implement both DFS and BFS for traversing graphs and solving problems like finding connected components.

2. **Find the shortest path in an unweighted graph using BFS.**
   - **Explanation:** Use BFS to find the shortest path from a source node to a target node in an unweighted graph.

3. **Dijkstra's Algorithm for finding the shortest path in a weighted graph.**
   - **Explanation:** Use Dijkstra's algorithm to find the shortest path from a source node to all other nodes in a graph with non-negative weights.

4. **Kruskal’s and Prim’s Algorithm for finding the Minimum Spanning Tree (MST).**
   - **Explanation:** Solve the MST problem using both Kruskal’s and Prim’s algorithms.

5. **Detect a cycle in a directed/undirected graph.**
   - **Explanation:** Use DFS to detect cycles in a directed or undirected graph.

---

## 7. **Sorting and Searching**

1. **Find the K-th largest element in an unsorted array.**
   - **Explanation:** Use quick select or heap-based methods to find the K-th largest element in an array.

2. **Implement Merge Sort and Quick Sort algorithms.**
   - **Explanation:** Solve the sorting problem using merge sort and quick sort, which are divide-and-conquer algorithms.

3. **Find the missing number in an array of 1 to N.**
   - **Explanation:** Use binary search or XOR to find the missing number in an array containing numbers from 1 to N.

4. **Find the first non-repeating character in a string.**
   - **Explanation:** Use a hashmap to store the frequency of characters and then iterate through the string to find the first non-repeating character.

5. **Implement Binary Search on a sorted array.**
   - **Explanation:** Implement the binary search algorithm to find an element in a sorted array in `O(log n)` time.

---

## 8. **Bit Manipulation**

1. **Check if a number is a power of two.**
   - **Explanation:** Use bitwise operations to check if a number is a power of two.

2. **Find the single non-repeating element in an array where every other element appears twice.**
   - **Explanation:** Use XOR to find the element that appears once in the array.

3. **Count the number of set bits (1s) in a number.**
   - **Explanation:** Use bitwise operations to count the number of `1`s in the binary representation of a number.

4. **Swap two numbers without using a temporary variable.**
   - **Explanation:** Use XOR to swap two numbers without using extra space.

5. **Find the Hamming distance between two integers.**
   - **Explanation:** Use bitwise XOR to calculate the number of differing bits between two numbers.

---

## 9. **Mathematical Algorithms**

1. **Find the greatest common divisor (GCD) of two numbers using Euclid’s Algorithm.**
   - **Explanation:** Use Euclid’s algorithm (repeated division) to find the GCD of two numbers efficiently.

2. **Check if a number is prime.**
   - **Explanation:** Implement a primality test to check whether a number is prime.

3. **Find the power of a number using binary exponentiation.**
   - **Explanation:** Use binary exponentiation to compute large powers in logarithmic time.

4. **Solve the "n-th Fibonacci number" using matrix exponentiation.**
   - **Explanation:** Use matrix exponentiation to solve the Fibonacci problem in logarithmic time.

5. **Find the factorial of a number using recursion.**
   - **Explanation:** Use recursion to compute the factorial of a number.

---

## 10. **String Algorithms**

1. **Check if two strings are anagrams.**
   - **Explanation:** Use sorting or a hashmap to check if two strings are anagrams of each other.

2. **Implement regular expression matching (like `.` and `*`).**
   - **Explanation:** Use dynamic programming or recursion to implement regular expression matching.

3. **Find the longest palindromic substring in a string.**
   - **Explanation:** Use dynamic programming or expand around center technique to find the longest palindromic substring.

4. **Implement string matching (e.g., KMP algorithm).**
   - **Explanation:** Use the KMP (Knuth-Morris-Pratt) algorithm to implement efficient string matching.

5. **Find all occurrences of a substring in a string.**
   - **Explanation:** Use the Rabin-Karp algorithm or KMP algorithm to find all occurrences of a substring in a given string.

---

This `.md` file contains a set of **advanced DSA interview questions** categorized by their respective algorithmic techniques. You can use this file for practice, preparation, or as a reference. Let me know if you'd like to add more questions or make any modifications!
