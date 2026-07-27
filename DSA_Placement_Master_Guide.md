# DSA + Placement Prep — Master Guide
**Starting point:** July 27, 2026 · **Target:** Backend Developer (Java) · **Runway:** ~10-14 weeks before peak hiring season

---

## 1. The Big Picture

- 7th Semester (Aug–Dec): some internship drives, not peak
- Peak hiring/rejection window: winter season
- You have real runway — enough to build properly instead of panic-grinding
- Core rule: **structure > streak.** Consistency matters more than a raw day-count number. A missed day spent deeply understanding one hard problem beats 4 shallow easy problems just to keep a streak alive.
- Keep Java (core + advanced + projects) running in parallel throughout — don't fully pause it once DSA ramps up. 20-30 min/day keeps it warm.

---

## 2. Prerequisite Map (read this before Phase 1)

Three things unlock roughly 60% of everything else. Get these genuinely comfortable first:

1. **Recursion** — unlocks DFS → Backtracking, Topological Sort, Union Find, and ALL of DP (via memoization → tabulation)
2. **Stack basics** — unlocks Monotonic Stack
3. **Vanilla Binary Search** — unlocks Modified Binary Search (rotated arrays, search-on-answer problems)

```
Recursion ─┬─→ DFS ─┬─→ Backtracking
           │        ├─→ Topological Sort
           │        └─→ Union Find
           └─→ Memoization → Tabulation → All DP patterns

Arrays/Sorting ─┬─→ Two Pointers ─→ Fast & Slow Pointers
                ├─→ Sliding Window
                ├─→ Merge Intervals
                └─→ Cyclic Sort

Binary Search (vanilla) ─→ Modified Binary Search
Stack ─→ Monotonic Stack
Heap ─┬─→ Top K Elements
      └─→ K-way Merge
Queue + Graph rep ─→ BFS
Bitwise ops (standalone)
```

---

## 3. Phase 0 — Basics Warm-up (Days 1–10, ~July 27 – Aug 5)

Quick-win topics. Don't overthink these — they build loop/modulo/array comfort you'll lean on everywhere later.

**Basic Maths** (Days 1–2): Count digits, reverse a number, palindrome number, largest digit, factorial, Armstrong check, perfect number, prime check, primes till N, GCD, LCM, divisors

**Basic Arrays** (Day 3): Sum of array, count odds, check sorted, reverse array

**Basic Hashing** (Day 3): Highest occurring element, second highest occurring, sum of highest+lowest frequency

**Basic Strings** (Days 4–5): Reverse string, palindrome check, largest odd number in string, longest common prefix, isomorphic string, rotate string, valid anagram, sort characters by frequency

**Basic Recursion** (Days 6–10 — spend the MOST time here relative to size):
Recursion theory, sum of first N numbers, factorial, sum of array elements (recursive), reverse a string, palindrome check (recursive), prime check (recursive), reverse an array (recursive), check sorted (recursive), sum of digits, Fibonacci

> ⚠️ Many people rush recursion because it "looks basic." Don't. Weak recursion here is the #1 hidden cause of struggling with DP/backtracking later.

---

## 4. Phase 1 — Data Structure Mechanics (Weeks 2–4, ~Aug 6 – Aug 26)

Goal: stop treating data structures as magic — implement them by hand.

**Week 2 (Aug 6–12): Arrays + Hashing + Binary Search fundamentals**
- Linear search, largest/second largest element, max consecutive ones, left rotate array (by 1, by K)
- Basic hashing theory
- Binary search: search X, lower bound, upper bound

**Week 3 (Aug 13–19): Linked List (Singly + Doubly) — full implementation**
- Singly LL: traversal, insertion (head/tail/kth/before value X), deletion (head/tail/kth/by value)
- Doubly LL: same operations + array-to-DLL conversion
- Get your hands dirty coding these raw — don't jump to LeetCode-style LL problems yet

**Week 4 (Aug 20–26): Stack/Queue implementations + Binary Tree traversals**
- Implement stack using array/LinkedList, queue using array/LinkedList, stack using queue, queue using stack
- Balanced Parenthesis (first real stack application)
- Binary Tree: inorder, preorder, postorder, level order, all-three-in-one-traversal
- Light intro only (conceptual, not mastery): BST intro, Heaps (heapify, build heap, min/max heap, Kth largest), Graph intro (traversal techniques, connected components), DP intro, Trie basics

---

## 5. Phase 2 — Pattern Practice on Your 275-Question Sheet (Weeks 5–13, ~Aug 27 – Oct 21)

Use the **275_Question_Sheet_By_Pattern.md** file (already made) — go pattern by pattern, easy → medium within each pattern, mostly skipping hard on the first pass.

| Week | Dates (approx) | Patterns |
|---|---|---|
| 5–6 | Aug 27 – Sep 9 | Two Pointers, Fast & Slow, Sliding Window, Merge Intervals, Cyclic Sort |
| 7 | Sep 10–16 | Monotonic Stack |
| 8 | Sep 17–23 | Modified Binary Search, Top K (Heap), K-way Merge |
| 9–10 | Sep 24 – Oct 7 | BFS, DFS, Topological Sort |
| 11 | Oct 8–14 | Backtracking/Subsets, Bitwise/XOR |
| 12–13 | Oct 15–28 | All DP patterns (0/1 Knapsack → Unbounded → LCS/LIS → Palindromes → Interval), then Union Find |

**Daily math:** 275 problems ÷ ~9 weeks of active sheet-solving ≈ 4 problems/day (Easy: 1-2/day, Medium: 2-3/day, Hard: skip for now).

---

## 6. Phase 3 — Consolidation (last 3-4 weeks before drives ramp up, ~late Oct – Nov)

Mindset shift, not new content:
- Stop chasing unseen problems
- **Redo** problems that gave you trouble the first time — repetition is where retention actually happens
- Timed practice: simulate interview pressure (25-30 min/problem, no lecture safety net)
- Weekly contests — not to grind, but consistency naturally improves rank
- Now selectively pick up Hard problems, prioritizing the clusters noted in the 275-sheet takeaways (DP, binary-search-on-answer, hard backtracking, KMP-based strings)

---

## 7. Fixing the "approach vs implementation" gap

If your code throws errors and the lecture's approach turns out totally different — the gap usually isn't understanding OR coding, it's **skipping approach validation** in between. Insert this step before writing any code:

1. State your approach in **one sentence** ("I'll use two pointers from both ends since it's sorted"). Can't state it in one sentence → you don't have an approach yet.
2. **Dry-run on paper** with a small example (5-6 elements), tracing variables by hand — not in your head.
3. Only if the dry-run actually reaches the correct answer → start coding.

When your approach turns out wrong anyway, diagnose *which* of these it was (they need different fixes):
- Didn't recognize the pattern at all
- Recognized it but implemented incorrectly
- Picked a working-but-non-optimal technique and got tripped up by constraints

Stick to the **LeetCode editor** for daily practice (faster iteration). Reach for IntelliJ only when debugging a genuine runtime bug you can't diagnose from the error message, or for OOP/LLD-style practice.

---

## 8. Recommended Educators

**DSA pattern/intuition:**
- Abdul Bari — best for genuinely understanding *why*, especially graphs/trees/DP
- Striver (takeUforward) — the A2Z sheet is literally what Sections 3–4 above are built from
- NeetCode — clean, short, English explanations, good for Phase 3 revision

**Java + DSA combined:**
- Kunal Kushwaha — free, fully in Java
- Apna College — has an active Java+DSA placement playlist
- Pepcoding (Sumit Malik) — particularly strong for recursion & backtracking intuition

**Core/Advanced Java:**
- Telusko — core Java + OOP
- Java Brains — once you move toward Spring/backend frameworks

**Revision closer to drives:**
- GeeksforGeeks YouTube — topic-wise quick revision

*Suggestion: pick ONE DSA spine (Striver or Abdul Bari) + ONE Java spine (Kunal Kushwaha or Apna College). Channel-hopping burns time without adding depth.*

---

## 9. Companion File
See **275_Question_Sheet_By_Pattern.md** for the full 275-question list already broken down by pattern, with a "Quick takeaways" section on where Tree/Graph/DP/Hashing concentration lies and where Hards cluster.
