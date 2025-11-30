# Algorithms for Big Tech Coding Interviews

## 1. Sorting Algorithms

### 1.1 Comparison-Based Sorting

**Key Algorithms:**

- **Bubble Sort**: O(n²) - Educational, rarely used
- **Selection Sort**: O(n²) - Simple but inefficient
- **Insertion Sort**: O(n²) - Good for small/nearly sorted arrays
- **Merge Sort**: O(n log n) - Stable, divide and conquer
- **Quick Sort**: O(n log n) average - Most commonly used
- **Heap Sort**: O(n log n) - In-place, uses heap

**Practice Problems:**

- Sort an Array
- Sort Colors (Dutch National Flag)
- Merge Sorted Arrays
- Kth Largest Element

**Free Resources:**

- [Sorting Algorithms - GeeksforGeeks](https://www.geeksforgeeks.org/sorting-algorithms/)
- [Sorting Visualizations - VisuAlgo](https://visualgo.net/en/sorting)
- [Sorting - MIT OCW](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/)

### 1.2 Non-Comparison Sorting

**Key Algorithms:**

- **Counting Sort**: O(n+k) - For integers in range
- **Radix Sort**: O(d*(n+k)) - For integers
- **Bucket Sort**: O(n+k) - For uniformly distributed data

**Free Resources:**

- [Counting Sort - GeeksforGeeks](https://www.geeksforgeeks.org/counting-sort/)
- [Radix Sort - GeeksforGeeks](https://www.geeksforgeeks.org/radix-sort/)

---

## 2. Searching Algorithms

### 2.1 Binary Search

**Key Concepts:**

- Search in sorted array: O(log n)
- Lower bound and upper bound
- Search space reduction
- Binary search on answer
- Variations (rotated array, 2D matrix)

**Practice Problems:**

- Binary Search
- Search in Rotated Sorted Array
- Find First and Last Position
- Search a 2D Matrix
- Median of Two Sorted Arrays
- Koko Eating Bananas

**Free Resources:**

- [Binary Search - GeeksforGeeks](https://www.geeksforgeeks.org/binary-search/)
- [Binary Search Patterns - LeetCode](https://leetcode.com/explore/learn/card/binary-search/)
- [Binary Search Tutorial - YouTube](https://www.youtube.com/watch?v=j5uXyPJ0Pew)

### 2.2 Other Search Techniques

**Key Concepts:**

- Linear search
- Jump search
- Interpolation search
- Exponential search

---

## 3. Graph Algorithms

### 3.1 Graph Traversal

**Breadth-First Search (BFS):**

- Level-by-level traversal
- Shortest path in unweighted graphs
- Time: O(V+E)

**Depth-First Search (DFS):**

- Explore as deep as possible
- Backtracking problems
- Time: O(V+E)

**Practice Problems:**

- Number of Islands
- Word Ladder
- Surrounded Regions
- All Paths From Source to Target
- Keys and Rooms

**Free Resources:**

- [BFS and DFS - GeeksforGeeks](https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph/)
- [Graph Traversal - VisuAlgo](https://visualgo.net/en/dfsbfs)

### 3.2 Shortest Path Algorithms

**Dijkstra's Algorithm:**

- Single-source shortest path
- Non-negative weights
- Time: O((V+E) log V) with min-heap

**Bellman-Ford Algorithm:**

- Handles negative weights
- Detects negative cycles
- Time: O(VE)

**Floyd-Warshall Algorithm:**

- All-pairs shortest path
- Time: O(V³)

**Practice Problems:**

- Network Delay Time
- Cheapest Flights Within K Stops
- Path with Maximum Probability

**Free Resources:**

- [Dijkstra's Algorithm - GeeksforGeeks](https://www.geeksforgeeks.org/dijkstras-shortest-path-algorithm-greedy-algo-7/)
- [Shortest Path - VisuAlgo](https://visualgo.net/en/sssp)
- [Graph Algorithms - CP-Algorithms](https://cp-algorithms.com/graph/dijkstra.html)

### 3.3 Minimum Spanning Tree

**Kruskal's Algorithm:**

- Uses Union-Find
- Time: O(E log E)

**Prim's Algorithm:**

- Uses priority queue
- Time: O(E log V)

**Practice Problems:**

- Min Cost to Connect All Points
- Connecting Cities With Minimum Cost

**Free Resources:**

- [MST Algorithms - GeeksforGeeks](https://www.geeksforgeeks.org/kruskals-minimum-spanning-tree-algorithm-greedy-algo-2/)

### 3.4 Topological Sort

**Key Concepts:**

- DAG (Directed Acyclic Graph)
- Kahn's algorithm (BFS-based)
- DFS-based approach
- Cycle detection

**Practice Problems:**

- Course Schedule
- Course Schedule II
- Alien Dictionary
- Parallel Courses

**Free Resources:**

- [Topological Sort - GeeksforGeeks](https://www.geeksforgeeks.org/topological-sorting/)
- [Topological Sort - YouTube](https://www.youtube.com/watch?v=eL-KzMXSXXI)

---

## 4. Dynamic Programming (DP)

### 4.1 One-Dimensional DP

**Key Patterns:**

- Fibonacci sequence
- House robber pattern
- Climbing stairs variations
- Decode ways

**Practice Problems:**

- Climbing Stairs
- House Robber
- Decode Ways
- Longest Increasing Subsequence
- Coin Change

**Free Resources:**

- [Dynamic Programming - GeeksforGeeks](https://www.geeksforgeeks.org/dynamic-programming/)
- [DP Patterns - LeetCode Discuss](https://leetcode.com/discuss/general-discussion/458695/dynamic-programming-patterns)

### 4.2 Two-Dimensional DP

**Key Patterns:**

- Grid-based problems
- Longest common subsequence
- Edit distance
- Matrix chain multiplication

**Practice Problems:**

- Unique Paths
- Minimum Path Sum
- Longest Common Subsequence
- Edit Distance
- Regular Expression Matching

### 4.3 Advanced DP Patterns

**Key Concepts:**

- Knapsack problems (0/1, unbounded)
- Palindrome partitioning
- String matching
- State machine DP
- Bitmask DP

**Practice Problems:**

- Partition Equal Subset Sum
- Target Sum
- Longest Palindromic Subsequence
- Burst Balloons
- Best Time to Buy and Sell Stock with Cooldown

**Free Resources:**

- [DP Tutorial - TopCoder](https://www.topcoder.com/thrive/articles/Dynamic%20Programming:%20From%20Novice%20to%20Advanced)
- [DP Patterns - YouTube Playlist](https://www.youtube.com/watch?v=oBt53YbR9Kk)
- [DP Guide - CP-Algorithms](https://cp-algorithms.com/dynamic_programming/intro-to-dp.html)

---

## 5. Greedy Algorithms

**Key Concepts:**

- Local optimal choice leads to global optimum
- Activity selection
- Huffman coding
- Fractional knapsack
- Interval scheduling

**Practice Problems:**

- Jump Game
- Gas Station
- Meeting Rooms II
- Non-overlapping Intervals
- Minimum Number of Arrows

**Free Resources:**

- [Greedy Algorithms - GeeksforGeeks](https://www.geeksforgeeks.org/greedy-algorithms/)
- [Greedy vs DP - YouTube](https://www.youtube.com/watch?v=ARvQcqJ_-NY)

---

## 6. Backtracking

**Key Concepts:**

- Exhaustive search with pruning
- Choice, constraint, goal
- DFS-based exploration
- Common patterns: permutations, combinations, subsets

**Practice Problems:**

- Permutations
- Combinations
- Subsets
- N-Queens
- Sudoku Solver
- Word Search
- Generate Parentheses

**Free Resources:**

- [Backtracking - GeeksforGeeks](https://www.geeksforgeeks.org/backtracking-algorithms/)
- [Backtracking Guide - LeetCode](https://leetcode.com/explore/learn/card/recursion-ii/472/backtracking/)
- [Backtracking Tutorial - YouTube](https://www.youtube.com/watch?v=Zq4upTEaQyM)

---

## 7. Divide and Conquer

**Key Concepts:**

- Divide problem into subproblems
- Solve recursively
- Combine solutions
- Master theorem for complexity

**Practice Problems:**

- Merge Sort
- Quick Sort
- Binary Search
- Maximum Subarray
- Pow(x, n)

**Free Resources:**

- [Divide and Conquer - GeeksforGeeks](https://www.geeksforgeeks.org/divide-and-conquer/)
- [Master Theorem - MIT OCW](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/)

---

## 8. Two Pointers / Sliding Window

**Key Concepts:**

- Two pointers (same/opposite direction)
- Sliding window (fixed/variable size)
- Fast and slow pointers

**Practice Problems:**

- Two Sum II
- Container With Most Water
- Trapping Rain Water
- Minimum Window Substring
- Longest Substring Without Repeating Characters
- Linked List Cycle

**Free Resources:**

- [Two Pointers - LeetCode](https://leetcode.com/tag/two-pointers/)
- [Sliding Window - YouTube](https://www.youtube.com/watch?v=GcW4mgmgSbw)

---

## 9. Bit Manipulation

**Key Concepts:**

- AND, OR, XOR, NOT operations
- Bit shifting
- Set, clear, toggle bits
- Count set bits
- Power of two
- XOR properties

**Practice Problems:**

- Single Number
- Number of 1 Bits
- Counting Bits
- Sum of Two Integers
- Reverse Bits
- Missing Number

**Free Resources:**

- [Bit Manipulation - GeeksforGeeks](https://www.geeksforgeeks.org/bits-manipulation-important-tactics/)
- [Bit Tricks - Stanford](https://graphics.stanford.edu/~seander/bithacks.html)
- [Bitwise Operations - YouTube](https://www.youtube.com/watch?v=NLKQEOgBAnw)

---

## 10. String Algorithms

### 10.1 Pattern Matching

**KMP Algorithm:**

- Linear time pattern matching
- Time: O(n+m)

**Rabin-Karp:**

- Rolling hash approach
- Time: O(n+m) average

**Practice Problems:**

- Implement strStr()
- Repeated String Match
- Shortest Palindrome

**Free Resources:**

- [KMP Algorithm - GeeksforGeeks](https://www.geeksforgeeks.org/kmp-algorithm-for-pattern-searching/)
- [String Matching - CP-Algorithms](https://cp-algorithms.com/string/string-hashing.html)

### 10.2 String Manipulation

**Key Concepts:**

- Palindrome checking
- String reversal
- Anagrams
- Subsequences

**Practice Problems:**

- Valid Palindrome
- Longest Palindromic Substring
- Group Anagrams
- Longest Common Prefix

---

## 11. Mathematical Algorithms

**Key Concepts:**

- Prime numbers (Sieve of Eratosthenes)
- GCD and LCM (Euclidean algorithm)
- Modular arithmetic
- Fast exponentiation
- Combinatorics
- Probability

**Practice Problems:**

- Pow(x, n)
- Count Primes
- Excel Sheet Column Number
- Happy Number
- Factorial Trailing Zeroes

**Free Resources:**

- [Math for Competitive Programming - GeeksforGeeks](https://www.geeksforgeeks.org/mathematical-algorithms/)
- [Number Theory - CP-Algorithms](https://cp-algorithms.com/algebra/)

---

## 12. Advanced Topics

### 12.1 Tree Algorithms

**Key Concepts:**

- Tree DP
- Lowest common ancestor (LCA)
- Tree diameter
- Serialize/deserialize

**Practice Problems:**

- Binary Tree Maximum Path Sum
- Serialize and Deserialize Binary Tree
- Lowest Common Ancestor
- Diameter of Binary Tree

### 12.2 Monotonic Stack/Queue

**Key Concepts:**

- Maintain increasing/decreasing order
- Next greater/smaller element
- Sliding window maximum

**Practice Problems:**

- Next Greater Element
- Daily Temperatures
- Largest Rectangle in Histogram
- Sliding Window Maximum

**Free Resources:**

- [Monotonic Stack - LeetCode](https://leetcode.com/tag/monotonic-stack/)

---

## Algorithm Complexity Cheat Sheet

| Algorithm     | Best       | Average        | Worst          | Space    |
|---------------|------------|----------------|----------------|----------|
| Bubble Sort   | O(n)       | O(n²)          | O(n²)          | O(1)     |
| Merge Sort    | O(n log n) | O(n log n)     | O(n log n)     | O(n)     |
| Quick Sort    | O(n log n) | O(n log n)     | O(n²)          | O(log n) |
| Binary Search | O(1)       | O(log n)       | O(log n)       | O(1)     |
| DFS/BFS       | -          | O(V+E)         | O(V+E)         | O(V)     |
| Dijkstra      | -          | O((V+E) log V) | O((V+E) log V) | O(V)     |

---

## Study Strategy

### Phase 1: Fundamentals (Weeks 1-2)

- Arrays, strings, two pointers
- Basic sorting and searching
- Hash tables

### Phase 2: Core Structures (Weeks 3-4)

- Linked lists, stacks, queues
- Binary trees and BST
- Basic recursion

### Phase 3: Intermediate (Weeks 5-8)

- Graphs (BFS, DFS)
- Dynamic programming basics
- Backtracking
- Heaps

### Phase 4: Advanced (Weeks 9-12)

- Advanced DP patterns
- Graph algorithms (Dijkstra, topological sort)
- Tries
- Bit manipulation
- String algorithms

### Phase 5: Mock Interviews (Weeks 13+)

- Timed practice
- System design basics
- Company-specific problems

---

## Essential Problem Lists

**NeetCode 150**: [neetcode.io/practice](https://neetcode.io/practice)
**Blind 75**: Classic curated list
**LeetCode Top Interview Questions
**: [leetcode.com/explore](https://leetcode.com/explore/interview/card/top-interview-questions-easy/)
**Grind 75**: [techinterviewhandbook.org/grind75](https://www.techinterviewhandbook.org/grind75)

---

## Free Online Courses

- **MIT 6.006 Introduction to Algorithms
  **: [MIT OCW](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/)
- **Princeton Algorithms Part I & II**: [Coursera](https://www.coursera.org/learn/algorithms-part1)
- **Stanford CS161 Algorithms
  **: [Stanford Online](https://www.youtube.com/playlist?list=PLXFMmlk03Dt7Q0xr1PIAriY5623cKiH7V)
- **Abdul Bari Algorithms
  **: [YouTube](https://www.youtube.com/watch?v=0IAPZzGSbME&list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O)

---

## Practice Platforms

- **LeetCode**: Best for interview prep
- **HackerRank**: Structured tracks
- **Codeforces**: Competitive programming
- **CodeChef**: Monthly contests
- **AtCoder**: Quality problems

## Pro Tips

1. Understand the pattern, not just the solution
2. Always analyze time and space complexity
3. Write clean, readable code with good variable names
4. Practice explaining your approach out loud
5. Learn to identify which algorithm/pattern to use
6. Master 2-3 problems per pattern before moving on
7. Revisit problems after 1 week, 1 month, 3 months
8. Focus on understanding WHY a solution works
