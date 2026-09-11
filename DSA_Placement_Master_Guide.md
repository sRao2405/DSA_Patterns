# DSA + Placement Prep — Master Guide

**Start Date:** September 5, 2026  
**Role Target:** Backend Developer (Java)  
**Peak Hiring Window:** February 2027  
**Runway:** ~22 Weeks  
**Status:** Phase 0 Completed | Phase 1 Completed through Arrays, Hashing, Linked Lists (Singly + Doubly), Stack & Queue Implementations

---

## 💡 How to Use This Guide

This is a living document, not a rigid schedule. Each week, spend two minutes updating your progress tracking and your **Struggled / Needs Revisit** list. If a topic runs over, let it run over.

> **Golden Rule:** **Structure beats streak.** One hard problem genuinely understood beats four easy ones solved just to keep a counter alive.

> **Java Continuity Note:** Keep Java running in the background for **30–45 min/day** (Core Java, Collections, Multithreading, or Spring Boot features). Never let your Java skills go cold.

---

## 🗺️ 1. Timeline at a Glance

| Phase | Window | Duration | Core Focus |
| :--- | :--- | :--- | :--- |
| **Phase 1 (Finish)** | Sep 6 – Sep 15 | ~1.5 Weeks | Trees, BST, Heaps & Graph Theory Intro |
| **Phase 2** | Sep 16 – Dec 15 | 13 Weeks | 275-Sheet Pattern Engine (~3–4 problems/day) |
| **Phase 3** | Dec 16 – Jan 15 | 4.5 Weeks | Consolidation, Spaced Repetition & Hard Clusters |
| **Phase 4** | Jan 16 – Feb 2027 | ~4 Weeks | Mock Interviews, CS Fundamentals & Peak Drives |

---

## 🧩 2. Prerequisite Dependency Map

```
                     ┌─► DFS ───┬─► Backtracking
                     │          ├─► Topological Sort
Recursion ───────────┼──────────┴─► Union Find
                     │
                     └─► Memoization ──► Tabulation ──► Dynamic Programming
```
```
                     ┌─► Two Pointers ──► Fast & Slow Pointers
Arrays / Sorting ────┼─► Sliding Window
                     ├─► Merge Intervals
                     └─► Cyclic Sort
```
```
Vanilla Binary Search ─────────────────► Modified Binary Search / Search-on-Answer
Stack ─────────────────────────────────► Monotonic Stack
Heap ──────────────────────────────────► Top K Elements / K-Way Merge
Queue + Graph Representation ──────────► BFS
Bitwise Operations ────────────────────► Bitmasking (Standalone)
```

**Quick Gut-Check:** Can you write a recursive function that reverses an array from memory and explain why the base case works out loud? If not, spend an evening patching recursion logic now.

---

## 🌲 3. Phase 1 (Finish) — Trees & Structural Fundamentals

**Window:** Sep 6 – Sep 15 (10 Days)

### **Tree Traversals (Sep 6 – Sep 9)**
- [X] Inorder, Preorder, and Postorder (Recursive **and** Iterative implementations)
- [X] Level Order Traversal (BFS on trees)
- [X] All-in-one Traversal strategy

### **Binary Search Trees & Heaps (Sep 10 – Sep 12)**
- [X] **BST:** Search, Insert, and Delete operations (implement by hand)
- [X] **Heaps:** Heapify algorithm, Build Heap in $O(N)$, Min/Max Heap mechanics, and "Kth Largest" application

### **Graphs & Advanced Structures (Sep 13 – Sep 15)**
- [ ] **Graph Representations:** Adjacency Matrix vs. Adjacency List
- [ ] **Graph Theory:** BFS and DFS traversal concepts (theory pass)
- [ ] **Tries:** Basic structure and node representation

---

## ⚙️ 4. Phase 2 — The 275-Sheet Pattern Engine

**Window:** Sep 16 – Dec 15 (13 Weeks / ~90 Days)  
**Target Pacing:** 275 problems $\div$ 90 days $\approx$ **3–4 problems/day** *(Easy: 1–2, Medium: 2–3, Hard: skip on first pass)*

| Week | Date Range | Pattern Focus | Key Skills & Sub-Topics |
| :---: | :--- | :--- | :--- |
| **W1–2** | Sep 16 – Sep 29 | Two Pointers, Fast & Slow, Sliding Window | Dynamic window bounds, cycle detection, pair-sum tricks |
| **W3** | Sep 30 – Oct 6 | Merge Intervals, Cyclic Sort | Overlapping intervals, in-place array placement |
| **W4** | Oct 7 – Oct 13 | Monotonic Stack | Next Greater/Smaller Element, Stock Span, Histogram |
| **W5–6** | Oct 14 – Oct 27 | Modified Binary Search, Top K, K-Way Merge | Rotated array search, search-on-answer, heap selection |
| **W7–9** | Oct 28 – Nov 17 | BFS, DFS, Topological Sort | Connected components, Kahn's algorithm, bipartite check |
| **W10** | Nov 18 – Nov 24 | Backtracking / Subsets, Bitwise & XOR | Decision trees, permutations, combinations, bitmasking |
| **W11–13** | Nov 25 – Dec 15 | Dynamic Programming & Union Find (DSU) | Knapsack, LCS/LIS, Palindromes, Interval DP, Disjoint Set |


## SDE Interview DSA — Complete Question List

A comprehensive roadmap and problem list categorized by key Data Structures and Algorithms patterns for Software Development Engineer (SDE) interview preparation.

---

## 1. Two Pointers ⭐⭐⭐⭐⭐

- [ ] Two Sum II – Input Array Is Sorted
- [ ] Valid Palindrome
- [ ] Remove Duplicates from Sorted Array
- [ ] Move Zeroes
- [ ] Squares of a Sorted Array
- [ ] 3Sum
- [ ] Container With Most Water
- [ ] Sort Colors
- [ ] Trapping Rain Water
- [ ] 3Sum Closest
- [ ] 4Sum
- [ ] Boats to Save People
- [ ] Backspace String Compare
- [ ] Merge Sorted Array

> **Core Problems:** 1–9

---

## 2. Fast & Slow Pointers ⭐⭐⭐⭐

- [ ] Middle of the Linked List
- [ ] Linked List Cycle
- [ ] Linked List Cycle II
- [ ] Happy Number
- [ ] Palindrome Linked List
- [ ] Reorder List
- [ ] Remove Nth Node From End of List
- [ ] Intersection of Two Linked Lists
- [ ] Find the Duplicate Number
- [ ] Circular Array Loop

> **Core Problems:** 1–7

---

## 3. Sliding Window ⭐⭐⭐⭐⭐

- [ ] Maximum Average Subarray I
- [ ] Maximum Number of Vowels in a Substring of Given Length
- [ ] Permutation in String
- [ ] Find All Anagrams in a String
- [ ] Longest Substring Without Repeating Characters
- [ ] Longest Repeating Character Replacement
- [ ] Max Consecutive Ones III
- [ ] Fruit Into Baskets
- [ ] Minimum Size Subarray Sum
- [ ] Longest Subarray of 1's After Deleting One Element
- [ ] Minimum Window Substring

> **Core Problems:** 3–7, 9, 11

---

## 4. Merge Intervals ⭐⭐⭐⭐

- [ ] Merge Intervals
- [ ] Insert Interval
- [ ] Non-overlapping Intervals
- [ ] Meeting Rooms
- [ ] Meeting Rooms II
- [ ] Interval List Intersections
- [ ] Minimum Number of Arrows to Burst Balloons
- [ ] Employee Free Time
- [ ] My Calendar I

> **Core Problems:** 1–5

---

## 5. Cyclic Sort ⭐⭐⭐

- [ ] Missing Number
- [ ] Find All Numbers Disappeared in an Array
- [ ] Find the Duplicate Number
- [ ] Set Mismatch
- [ ] First Missing Positive
- [ ] Find All Duplicates in an Array
- [ ] Kth Missing Positive Number

> **Core Problems:** 1, 2, 5, 6

---

## 6. Monotonic Stack ⭐⭐⭐⭐⭐

- [ ] Next Greater Element I
- [ ] Next Greater Element II
- [ ] Daily Temperatures
- [ ] Next Smaller Element
- [ ] Previous Smaller Element
- [ ] Online Stock Span
- [ ] Largest Rectangle in Histogram
- [ ] Trapping Rain Water
- [ ] Remove K Digits
- [ ] Sum of Subarray Minimums
- [ ] Sum of Subarray Ranges
- [ ] Maximal Rectangle

> **Core Problems:** 1–8

---

## 7. Modified Binary Search ⭐⭐⭐⭐⭐

- [ ] Search in Rotated Sorted Array
- [ ] Search in Rotated Sorted Array II
- [ ] Find Minimum in Rotated Sorted Array
- [ ] Find Peak Element
- [ ] Single Element in a Sorted Array
- [ ] Search a 2D Matrix
- [ ] Find First and Last Position of Element in Sorted Array
- [ ] Find K Closest Elements
- [ ] Koko Eating Bananas
- [ ] Capacity to Ship Packages Within D Days
- [ ] Split Array Largest Sum

> **Core Problems:** 1, 3, 4, 5, 7, 9

---

## 8. Top K Elements / Heap ⭐⭐⭐⭐⭐

- [ ] Kth Largest Element in an Array
- [ ] Top K Frequent Elements
- [ ] K Closest Points to Origin
- [ ] Kth Largest Element in a Stream
- [ ] Top K Frequent Words
- [ ] Find K Pairs with Smallest Sums
- [ ] Sort Characters By Frequency
- [ ] Kth Smallest Element in a Sorted Matrix

> **Core Problems:** 1–6

---

## 9. K-Way Merge ⭐⭐⭐⭐

- [ ] Merge K Sorted Lists
- [ ] Kth Smallest Element in a Sorted Matrix
- [ ] Find K Pairs with Smallest Sums
- [ ] Kth Smallest Number in M Sorted Lists
- [ ] Smallest Range Covering Elements from K Lists
- [ ] Merge K Sorted Arrays
- [ ] Ugly Number II

> **Core Problems:** 1–5  
> **Note:** *Kth Smallest in Sorted Matrix* and *Find K Pairs with Smallest Sums* overlap with Top-K. You don't need to solve them twice.

---

## 10. BFS / DFS ⭐⭐⭐⭐⭐

### Trees
- [ ] Binary Tree Level Order Traversal
- [ ] Maximum Depth of Binary Tree

### Graphs / Grids
- [ ] Number of Islands
- [ ] Clone Graph
- [ ] Flood Fill
- [ ] Rotting Oranges
- [ ] Number of Provinces
- [ ] Pacific Atlantic Water Flow
- [ ] Surrounded Regions
- [ ] Word Ladder
- [ ] Shortest Path in Binary Matrix
- [ ] Course Schedule

> **Core Problems:** Number of Islands, Clone Graph, Flood Fill, Rotting Oranges, Level Order Traversal, Number of Provinces.

---

## 11. Topological Sort ⭐⭐⭐⭐⭐

- [ ] Course Schedule
- [ ] Course Schedule II
- [ ] Alien Dictionary
- [ ] Find Eventual Safe States
- [ ] Parallel Courses
- [ ] Minimum Height Trees

> **Core Problems:** 1, 2, 3  
> **Key Approaches:**  
> - **Kahn's Algorithm:** BFS + Indegree  
> - **DFS:** Cycle Detection

---

## 12. Backtracking / Subsets ⭐⭐⭐⭐⭐

- [ ] Subsets
- [ ] Permutations
- [ ] Combination Sum
- [ ] Combination Sum II
- [ ] Letter Combinations of a Phone Number
- [ ] Generate Parentheses
- [ ] Word Search
- [ ] Palindrome Partitioning
- [ ] N-Queens
- [ ] Sudoku Solver

> **Core Problems:** 1–7  
> **Fundamental Pattern:**  
> `Choose` ➔ `Explore` ➔ `Undo`

---

## 13. Bitwise & XOR ⭐⭐⭐⭐

- [ ] Single Number
- [ ] Missing Number
- [ ] Number of 1 Bits
- [ ] Counting Bits
- [ ] Reverse Bits
- [ ] Power of Two
- [ ] Single Number II
- [ ] Sum of Two Integers

> **Core Problems:** 1, 2, 3, 6, 7  
> **Important Concepts & Identities:**  
> - `x ^ x = 0`  
> - `x ^ 0 = x`  
> - `a ^ b ^ a = b`  
> - `n & (n - 1)` (clears lowest set bit)

---

## 14. Dynamic Programming ⭐⭐⭐⭐⭐

### Beginner / 1D DP
- [ ] Climbing Stairs
- [ ] House Robber
- [ ] House Robber II
- [ ] Coin Change
- [ ] Word Break
- [ ] Decode Ways

### Grid DP
- [ ] Unique Paths
- [ ] Minimum Path Sum

### Knapsack
- [ ] Partition Equal Subset Sum
- [ ] 0/1 Knapsack

### Sequence / String DP
- [ ] Longest Increasing Subsequence
- [ ] Longest Common Subsequence
- [ ] Edit Distance

> **Core Problems:** 1–4, 7, 9, 11, 12  
> **Learning Progression:**  
> `Recursion` ➔ `Memoization` ➔ `Tabulation` ➔ `Space Optimization`

---

## 15. Union Find / DSU ⭐⭐⭐⭐

- [ ] Number of Provinces
- [ ] Redundant Connection
- [ ] Accounts Merge
- [ ] Number of Connected Components
- [ ] Most Stones Removed with Same Row or Column
- [ ] Satisfiability of Equality Equations
- [ ] Kruskal's Minimum Spanning Tree

> **Core Problems:** 1, 2, 3, 7
SDE_Interview_DSA_Question_List.md
Displaying SDE_Interview_DSA_Question_List.md.



### **Struggled / Needs Revisit Tracker**

| Date | Pattern Name | Problem Title | Root Cause / Failure Mode |
| :---: | :--- | :--- | :--- |
| *Example* | *Sliding Window* | *Longest Substring Without Repeating Chars* | *Forgot to update left pointer boundary condition* |
| | | | |
| | | | |

---

## 🔁 5. Phase 3 — Consolidation & Hard Clusters

**Window:** Dec 16 – Jan 15 (4.5 Weeks)

### **Spaced Repetition Pass (Dec 16 – Dec 31)**
- [ ] Re-solve all entries in your **Struggled / Needs Revisit** tracker.
- [ ] Ignore problems you solved easily on your first attempt.

### **Selective Hard Clusters Pass (Jan 1 – Jan 15)**
- [ ] Binary Search on Answer (Hard variations)
- [ ] Advanced DP (State Machine DP, Bitmask DP)
- [ ] Advanced Graph / Topological Sort variations

### **Timed Execution Practice**
- [ ] Complete Medium problems within 25–30 minutes without hints.
- [ ] Participate in weekly LeetCode/CodeChef contests to practice speed under clock pressure.

---

## 🔍 6. The Approach-Validation Checklist

Run this 3-step check on paper **before** writing code on LeetCode:

```
[ Step 1: One-Sentence Approach ] ──► [ Step 2: Dry-Run on Paper ] ──► [ Step 3: Write Code ]
```

1. **State your approach in one sentence:** *"Use two pointers moving inward because the array is sorted."* If you cannot state it simply, you do not have an approach yet.
2. **Dry-run on paper:** Trace variables manually using a small 5–6 element test case.
3. **Write code:** Begin implementation only after your paper trace yields the correct result.

> **Diagnosing Execution Errors:**
> * **Did not recognize the pattern:** Revisit that pattern's core conceptual problems.
> * **Recognized pattern, but implementation failed:** Practice translating pseudocode to code slowly.
> * **Picked sub-optimal approach:** Identify which input constraint was missed and why it eliminated your chosen technique.

---

## 🎯 7. Phase 4 — Final Sprint & Peak Hiring Window

**Window:** Jan 16 – Feb 2027 Onward

### **Mock Interviews & Communication**
- [ ] Complete 2–3 mock interviews weekly (peer or platform-based).
- [ ] Practice explaining your one-sentence approach and dry-run out loud before writing code.

### **CS Fundamentals (45 Min Daily Block)**
- [ ] **Operating Systems:** Concurrency, Process vs. Thread, Memory Management, Deadlocks.
- [ ] **DBMS & SQL:** Indexing, Transactions, ACID properties, complex SQL queries.
- [ ] **Computer Networks:** TCP/IP stack, HTTP/HTTPS, OSI Model.

### **Java Backend Polish**
- [ ] Master Core Java details (Java 8+ Features, Memory Model, Garbage Collection, Locks & Multithreading).
- [ ] Polish a presentable Spring Boot REST API project with clear architecture details.

---

## 📚 8. Educator Reference Matrix

| Preparation Area | Primary Resource | Secondary / Revision Resource |
| :--- | :--- | :--- |
| **DSA Patterns & Intuition** | Striver (takeUforward A2Z Sheet) | Abdul Bari (Graphs, Trees, DP) |
| **Fast Revision (Phase 3)** | NeetCode | GeeksforGeeks YouTube |
| **Java + DSA Combined** | Kunal Kushwaha | Pepcoding (Recursion & Backtracking) |
| **Core Java & Frameworks** | Telusko | Java Brains (Spring Boot) |

---

## 🔄 9. Weekly Review Ritual (Every Sunday)

Spend 5 minutes every Sunday checking these key metrics:

1. **Pacing Check:** Did you hit your problem target for the week?
2. **Failure Analysis:** Are there common patterns in your **Struggled** list (e.g., missing base cases, wrong loop bounds)?
3. **Java Check:** Did you maintain your daily 30–45 minute Java study habit?
4. **Action Item:** What is the single main change you will make next week?
