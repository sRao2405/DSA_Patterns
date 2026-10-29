# DSA + Placement Prep — Master Guide

* **Start Date:** September 5, 2026
* **Role Target:** Backend Developer (Java)
* **Peak Hiring Window:** February 2027
* **Last Updated:** October 29, 2026 (timeline re-baselined)
* **Runway Remaining:** ~14 Weeks (Oct 30 → early Feb 2027)
* **Status:** Phase 0 ✅ | Phase 1 ✅ (Arrays, Hashing, Linked Lists, Stack & Queue, Trees, BST, Heaps, Graph Intro, Tries) | **Phase 2 🔄 in progress — 9 problems solved**

---

## 💡 How to Use This Guide

This is a living document, not a rigid schedule. Each week, spend two minutes updating your progress tracking and your **Struggled / Needs Revisit list**. If a topic runs over, let it run over.

> **Golden Rule:** Structure beats streak. One hard problem genuinely understood beats four easy ones solved just to keep a counter alive.

> **Java Continuity Note:** Keep Java running in the background for 30–45 min/day (Core Java, Collections, Multithreading, or Spring Boot features). Never let your Java skills go cold.

> **Re-plan Note (Oct 29):** The original schedule assumed ~3–4 problems/day from Sep 16. Actual progress is ~9 problems into Phase 2, so the remaining patterns have been re-sequenced from **Oct 30** at a sustainable **~2 problems/day (core problems first)**. Phase 3 was compressed to absorb the slip; Phase 4 start date is unchanged.

---

## 📊 Progress Snapshot (as of Oct 29, 2026)

| Pattern | Solved | Total | Status |
| :--- | :---: | :---: | :--- |
| Two Pointers | 4 | 14 | 🔄 Resume |
| Fast & Slow Pointers | 2 | 10 | 🔄 Resume |
| Sliding Window | 2 | 11 | 🔄 Resume |
| Merge Intervals | 1 | 9 | 🔄 Resume |
| Cyclic Sort | 0 | 7 | ⏳ Not started |
| Monotonic Stack | 0 | 12 | ⏳ Not started |
| Modified Binary Search | 0 | 11 | ⏳ Not started |
| Top K Elements / Heap | 0 | 8 | ⏳ Not started |
| K-Way Merge | 0 | 7 | ⏳ Not started |
| BFS / DFS | 0 | 12 | ⏳ Not started |
| Topological Sort | 0 | 6 | ⏳ Not started |
| Backtracking / Subsets | 0 | 10 | ⏳ Not started |
| Bitwise & XOR | 0 | 8 | ⏳ Not started |
| Dynamic Programming | 0 | 13 | ⏳ Not started |
| Union Find / DSU | 0 | 7 | ⏳ Not started |
| **Total** | **9** | **~145** | **~130 remaining (overlaps counted once)** |

---

## 🗺️ 1. Timeline at a Glance (Re-baselined)

| Phase | Window | Duration | Core Focus |
| :--- | :--- | :--- | :--- |
| **Phase 1** ✅ | Sep 6 – Sep 15 | 1.5 Weeks | Trees, BST, Heaps & Graph Theory Intro — **Completed** |
| **Phase 2** 🔄 | Sep 16 – Dec 31 *(resumed Oct 30)* | ~9 Weeks remaining | Pattern Engine (~2 problems/day, core first) |
| **Phase 3** | Jan 1 – Jan 15 | 2 Weeks | Consolidation, Spaced Repetition & Hard Clusters |
| **Phase 4** | Jan 16 – Feb 2027 | ~4 Weeks | Mock Interviews, CS Fundamentals & Peak Drives |

---

## 🧩 2. Prerequisite Dependency Map

```
Recursion ────────────────┬─► DFS ───────────────────┬─► Backtracking
                          │                          ├─► Topological Sort
                          │                          └─► Union Find
                          │
                          └─► Memoization ───────────► Tabulation ──────────► Dynamic Programming

Arrays / Sorting ─────────┬─► Two Pointers ──────────► Fast & Slow Pointers
                          ├─► Sliding Window
                          ├─► Merge Intervals
                          └─► Cyclic Sort

Vanilla Binary Search ───────────────────────────────► Modified Binary Search / Search-on-Answer

Stack ───────────────────────────────────────────────► Monotonic Stack

Heap ────────────────────────────────────────────────► Top K Elements / K-Way Merge

Queue + Graph Representation ────────────────────────► BFS

Bitwise Operations ───────────────────────────────────► Bitmasking (Standalone)
```

> **Quick Gut-Check:** Can you write a recursive function that reverses an array from memory and explain why the base case works out loud? If not, spend an evening patching recursion logic now.

---

## 🌲 3. Phase 1 ✅ — Trees & Structural Fundamentals (Completed)
**Window:** Sep 6 – Sep 15

### Tree Traversals
* [X] Inorder, Preorder, and Postorder (Recursive and Iterative implementations)
* [X] Level Order Traversal (BFS on trees)
* [X] All-in-one Traversal strategy

### Binary Search Trees & Heaps
* [X] **BST:** Search, Insert, and Delete operations (implement by hand)
* [X] **Heaps:** Heapify algorithm, Build Heap in $\mathcal{O}(N)$, Min/Max Heap mechanics, and "Kth Largest" application

### Graphs & Advanced Structures
* [X] **Graph Representations:** Adjacency Matrix vs. Adjacency List
* [X] **Graph Theory:** BFS and DFS traversal concepts (theory pass)
* [X] **Tries:** Basic structure and node representation

---

## ⚙️ 4. Phase 2 — The Pattern Engine (Re-baselined)
**Window:** Oct 30 – Dec 31 (~9 Weeks / 63 Days)
**Target Pacing:** ~130 remaining problems ÷ 63 days ≈ **2 problems/day** *(Easy: 1–2, Medium: 2–3, Hard: skip on first pass)*. Always do ⭐ **Core Problems** first; do the rest only if time allows.

| Week | Date Range | Pattern Focus | Key Skills & Sub-Topics |
| :--- | :--- | :--- | :--- |
| **W1** | Oct 30 – Nov 5 | Finish Two Pointers, Fast & Slow | Pair-sum tricks, cycle detection, linked-list pointer manipulation |
| **W2** | Nov 6 – Nov 12 | Finish Sliding Window, Merge Intervals | Dynamic window bounds, overlapping intervals |
| **W3** | Nov 13 – Nov 19 | Cyclic Sort, Monotonic Stack | In-place array placement, Next Greater/Smaller, Histogram |
| **W4** | Nov 20 – Nov 26 | Modified Binary Search, Top K Elements | Rotated array search, search-on-answer, heap selection |
| **W5** | Nov 27 – Dec 3 | K-Way Merge, BFS / DFS | Merge K lists, connected components, grid traversal, multi-source BFS |
| **W6** | Dec 4 – Dec 10 | Topological Sort, Backtracking / Subsets | Kahn's algorithm, cycle detection, permutations, combinations |
| **W7** | Dec 11 – Dec 17 | Bitwise & XOR, Union Find (DSU), start DP | XOR tricks, disjoint sets, 1D DP basics |
| **W8–9** | Dec 18 – Dec 31 | Dynamic Programming | Knapsack, LCS/LIS, Edit Distance, Grid DP |

> **Fallback rule:** If you fall behind again, cut *non-core* problems first (and for Cyclic Sort / Bitwise, do core-only). Never cut Binary Search, BFS/DFS, Backtracking, or DP core problems — they are the highest-frequency interview topics.

---

## SDE Interview DSA — Complete Question List
A comprehensive roadmap and problem list categorized by key Data Structures and Algorithms patterns for Software Development Engineer (SDE) interview preparation.

### 1. Two Pointers ⭐⭐⭐⭐⭐  *(4 / 14)*
* [X] Two Sum II – Input Array Is Sorted
* [ ] Valid Palindrome
* [ ] Remove Duplicates from Sorted Array
* [X] Move Zeroes
* [X] Squares of a Sorted Array
* [X] 3Sum
* [ ] Container With Most Water
* [ ] Sort Colors
* [ ] Trapping Rain Water
* [ ] 3Sum Closest
* [ ] 4Sum
* [ ] Boats to Save People
* [ ] Backspace String Compare
* [ ] Merge Sorted Array

**Core Problems:** 1–9

### 2. Fast & Slow Pointers ⭐⭐⭐⭐  *(2 / 10)*
* [X] Middle of the Linked List
* [X] Linked List Cycle
* [ ] Linked List Cycle II
* [ ] Happy Number
* [ ] Palindrome Linked List
* [ ] Reorder List
* [ ] Remove Nth Node From End of List
* [ ] Intersection of Two Linked Lists
* [ ] Find the Duplicate Number
* [ ] Circular Array Loop

**Core Problems:** 1–7

### 3. Sliding Window ⭐⭐⭐⭐⭐  *(2 / 11)*
* [ ] Maximum Average Subarray I
* [ ] Maximum Number of Vowels in a Substring of Given Length
* [ ] Permutation in String
* [ ] Find All Anagrams in a String
* [ ] Longest Substring Without Repeating Characters
* [ ] Longest Repeating Character Replacement
* [X] Max Consecutive Ones III
* [X] Fruit Into Baskets
* [ ] Minimum Size Subarray Sum
* [ ] Longest Subarray of 1's After Deleting One Element
* [ ] Minimum Window Substring

**Core Problems:** 3–7, 9, 11

### 4. Merge Intervals ⭐⭐⭐⭐  *(1 / 9)*
* [X] Merge Intervals
* [ ] Insert Interval
* [ ] Non-overlapping Intervals
* [ ] Meeting Rooms
* [ ] Meeting Rooms II
* [ ] Interval List Intersections
* [ ] Minimum Number of Arrows to Burst Balloons
* [ ] Employee Free Time
* [ ] My Calendar I

**Core Problems:** 1–5

### 5. Cyclic Sort ⭐⭐⭐  *(0 / 7)*
* [ ] Missing Number
* [ ] Find All Numbers Disappeared in an Array
* [ ] Find the Duplicate Number
* [ ] Set Mismatch
* [ ] First Missing Positive
* [ ] Find All Duplicates in an Array
* [ ] Kth Missing Positive Number

**Core Problems:** 1, 2, 5, 6

### 6. Monotonic Stack ⭐⭐⭐⭐⭐  *(0 / 12)*
* [ ] Next Greater Element I
* [ ] Next Greater Element II
* [ ] Daily Temperatures
* [ ] Next Smaller Element
* [ ] Previous Smaller Element
* [ ] Online Stock Span
* [ ] Largest Rectangle in Histogram
* [ ] Trapping Rain Water
* [ ] Remove K Digits
* [ ] Sum of Subarray Minimums
* [ ] Sum of Subarray Ranges
* [ ] Maximal Rectangle

**Core Problems:** 1–8

### 7. Modified Binary Search ⭐⭐⭐⭐⭐  *(0 / 11)*
* [ ] Search in Rotated Sorted Array
* [ ] Search in Rotated Sorted Array II
* [ ] Find Minimum in Rotated Sorted Array
* [ ] Find Peak Element
* [ ] Single Element in a Sorted Array
* [ ] Search a 2D Matrix
* [ ] Find First and Last Position of Element in Sorted Array
* [ ] Find K Closest Elements
* [ ] Koko Eating Bananas
* [ ] Capacity to Ship Packages Within D Days
* [ ] Split Array Largest Sum

**Core Problems:** 1, 3, 4, 5, 7, 9

### 8. Top K Elements / Heap ⭐⭐⭐⭐⭐  *(0 / 8)*
* [ ] Kth Largest Element in an Array
* [ ] Top K Frequent Elements
* [ ] K Closest Points to Origin
* [ ] Kth Largest Element in a Stream
* [ ] Top K Frequent Words
* [ ] Find K Pairs with Smallest Sums
* [ ] Sort Characters By Frequency
* [ ] Kth Smallest Element in a Sorted Matrix

**Core Problems:** 1–6

### 9. K-Way Merge ⭐⭐⭐⭐  *(0 / 7)*
* [ ] Merge K Sorted Lists
* [ ] Kth Smallest Element in a Sorted Matrix
* [ ] Find K Pairs with Smallest Sums
* [ ] Kth Smallest Number in M Sorted Lists
* [ ] Smallest Range Covering Elements from K Lists
* [ ] Merge K Sorted Arrays
* [ ] Ugly Number II

**Core Problems:** 1–5  
*Note: Kth Smallest in Sorted Matrix and Find K Pairs with Smallest Sums overlap with Top-K. You don't need to solve them twice.*

### 10. BFS / DFS ⭐⭐⭐⭐⭐  *(0 / 12)*
#### Trees
* [ ] Binary Tree Level Order Traversal
* [ ] Maximum Depth of Binary Tree

#### Graphs / Grids
* [ ] Number of Islands
* [ ] Clone Graph
* [ ] Flood Fill
* [ ] Rotting Oranges
* [ ] Number of Provinces
* [ ] Pacific Atlantic Water Flow
* [ ] Surrounded Regions
* [ ] Word Ladder
* [ ] Shortest Path in Binary Matrix
* [ ] Course Schedule

**Core Problems:** Number of Islands, Clone Graph, Flood Fill, Rotting Oranges, Level Order Traversal, Number of Provinces.

### 11. Topological Sort ⭐⭐⭐⭐⭐  *(0 / 6)*
* [ ] Course Schedule
* [ ] Course Schedule II
* [ ] Alien Dictionary
* [ ] Find Eventual Safe States
* [ ] Parallel Courses
* [ ] Minimum Height Trees

**Core Problems:** 1, 2, 3  
**Key Approaches:**
* Kahn's Algorithm: BFS + Indegree
* DFS: Cycle Detection

### 12. Backtracking / Subsets ⭐⭐⭐⭐⭐  *(0 / 10)*
* [ ] Subsets
* [ ] Permutations
* [ ] Combination Sum
* [ ] Combination Sum II
* [ ] Letter Combinations of a Phone Number
* [ ] Generate Parentheses
* [ ] Word Search
* [ ] Palindrome Partitioning
* [ ] N-Queens
* [ ] Sudoku Solver

**Core Problems:** 1–7  
**Fundamental Pattern:** $\text{Choose} \longrightarrow \text{Explore} \longrightarrow \text{Undo}$

### 13. Bitwise & XOR ⭐⭐⭐⭐  *(0 / 8)*
* [ ] Single Number
* [ ] Missing Number
* [ ] Number of 1 Bits
* [ ] Counting Bits
* [ ] Reverse Bits
* [ ] Power of Two
* [ ] Single Number II
* [ ] Sum of Two Integers

**Core Problems:** 1, 2, 3, 6, 7  

### 14. Dynamic Programming ⭐⭐⭐⭐⭐  *(0 / 13)*
#### Beginner / 1D DP
* [ ] Climbing Stairs
* [ ] House Robber
* [ ] House Robber II
* [ ] Coin Change
* [ ] Word Break
* [ ] Decode Ways

#### Grid DP
* [ ] Unique Paths
* [ ] Minimum Path Sum

#### Knapsack
* [ ] Partition Equal Subset Sum
* [ ] 0/1 Knapsack

#### Sequence / String DP
* [ ] Longest Increasing Subsequence
* [ ] Longest Common Subsequence
* [ ] Edit Distance

**Core Problems:** 1–4, 7, 9, 11, 12  

### 15. Union Find / DSU ⭐⭐⭐⭐  *(0 / 7)*
* [ ] Number of Provinces
* [ ] Redundant Connection
* [ ] Accounts Merge
* [ ] Number of Connected Components
* [ ] Most Stones Removed with Same Row or Column
* [ ] Satisfiability of Equality Equations
* [ ] Kruskal's Minimum Spanning Tree

**Core Problems:** 1, 2, 3, 7

---

## Struggled / Needs Revisit Tracker

| Date | Pattern Name | Problem Title | Root Cause / Failure Mode |
| :--- | :--- | :--- | :--- |
| *Example* | Sliding Window | Longest Substring Without Repeating Chars | Forgot to update left pointer boundary condition |
| | | | |

---

## 🔁 5. Phase 3 — Consolidation & Hard Clusters (Compressed)
**Window:** Jan 1 – Jan 15 (2 Weeks)

### Spaced Repetition Pass (Jan 1 – Jan 7)
* [ ] Re-solve all entries in your **Struggled / Needs Revisit tracker**.
* [ ] Ignore problems you solved easily on your first attempt.

### Selective Hard Clusters Pass (Jan 8 – Jan 15)
* [ ] Binary Search on Answer (Hard variations)
* [ ] Advanced DP (State Machine DP, Bitmask DP) — *only if core DP is solid*
* [ ] Advanced Graph / Topological Sort variations

### Timed Execution Practice
* [ ] Complete **Medium** problems within **25–30 minutes** without hints.
* [ ] Participate in weekly LeetCode/CodeChef contests to practice speed under clock pressure.

---

## 🔍 6. The Approach-Validation Checklist

Run this 3-step check on paper before writing code on LeetCode:

$$
\text{[ Step 1: One-Sentence Approach ]} \longrightarrow \text{[ Step 2: Dry-Run on Paper ]} \longrightarrow \text{[ Step 3: Write Code ]}
$$

1. **State your approach in one sentence:** e.g., *"Use two pointers moving inward because the array is sorted."* If you cannot state it simply, you do not have an approach yet.
2. **Dry-run on paper:** Trace variables manually using a small 5–6 element test case.
3. **Write code:** Begin implementation only after your paper trace yields the correct result.

### Diagnosing Execution Errors:
* **Did not recognize the pattern:** Revisit that pattern's core conceptual problems.
* **Recognized pattern, but implementation failed:** Practice translating pseudocode to code slowly.
* **Picked sub-optimal approach:** Identify which input constraint was missed and why it eliminated your chosen technique.

---

## 🎯 7. Phase 4 — Final Sprint & Peak Hiring Window
**Window:** Jan 16 – Feb 2027 Onward

### Mock Interviews & Communication
* [ ] Complete 2–3 mock interviews weekly (peer or platform-based).
* [ ] Practice explaining your one-sentence approach and dry-run out loud before writing code.

### CS Fundamentals (45 Min Daily Block)
* [ ] **Operating Systems:** Concurrency, Process vs. Thread, Memory Management, Deadlocks.
* [ ] **DBMS & SQL:** Indexing, Transactions, ACID properties, complex SQL queries.
* [ ] **Computer Networks:** TCP/IP stack, HTTP/HTTPS, OSI Model.

### Java Backend Polish
* [ ] Master Core Java details (Java 8+ Features, Memory Model, Garbage Collection, Locks & Multithreading).
* [ ] Polish a presentable Spring Boot REST API project with clear architecture details.

> **Tip:** Since Phase 2 now runs to Dec 31, start the CS Fundamentals block lightly (15–20 min/day) from mid-December so Phase 4 isn't a cold start.

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
1. **Pacing Check:** Did you hit your problem target for the week (~14 problems at 2/day)?
2. **Failure Analysis:** Are there common patterns in your Struggled list (e.g., missing base cases, wrong loop bounds)?
3. **Java Check:** Did you maintain your daily 30–45 minute Java study habit?
4. **Progress Snapshot:** Update the solved counts in the table at the top.
5. **Action Item:** What is the single main change you will make next week?
