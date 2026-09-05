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
- [ ] Inorder, Preorder, and Postorder (Recursive **and** Iterative implementations)
- [ ] Level Order Traversal (BFS on trees)
- [ ] All-in-one Traversal strategy

### **Binary Search Trees & Heaps (Sep 10 – Sep 12)**
- [ ] **BST:** Search, Insert, and Delete operations (implement by hand)
- [ ] **Heaps:** Heapify algorithm, Build Heap in $O(N)$, Min/Max Heap mechanics, and "Kth Largest" application

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
