# Optimal Garage Pairing Using Recursion

**Language:** C  
**Course:** COP 3502C – Computer Science I  
**Focus:** Recursion, Optimization, AI-Assisted Problem Solving

---

## Overview

This project computes the **minimum total distance** required to connect garages using expressways. Given the coordinates of **2n garages**, the program pairs them so that each garage is used exactly once while minimizing the overall distance.

The solution explores all valid pairings using **recursive permutations** and applies **AI-assisted optimization** to improve performance for larger inputs.

---

## AI-Assisted Optimization

This assignment explicitly required the use of **AI tools (ChatGPT)** to optimize the program.

- Initial solution worked correctly for small inputs (n ≤ 5)
- AI assistance was used to analyze performance bottlenecks
- ChatGPT helped introduce **early pruning**, terminating recursive branches when partial distances exceeded the current best solution
- Optimization preserved the required recursive and permutation-based structure

This demonstrates **responsible and effective use of AI** to improve algorithm efficiency while maintaining correctness.

---

## Key Features

- Recursive permutation generation using a `used[]` array
- Early pruning to drastically reduce the search space
- Euclidean distance calculations between garage coordinates
- Deterministic output with strict formatting requirements
- Improved runtime performance for larger values of *n*

---

## Technical Skills Demonstrated

- C Programming
- Recursion & Backtracking
- Permutation Algorithms
- Algorithm Optimization
- AI-Assisted Development
- Dynamic Memory Management
- Floating-Point Precision

---

## Algorithm Summary

1. Recursively generate permutations of garage indices  
2. Pair garages sequentially from the permutation  
3. Accumulate distances as each pair is formed  
4. Prune recursion when partial distance exceeds the best known solution  
5. Store and output the optimal pairing  

---

## Constraints

- No file I/O (stdin/stdout only)
- Recursive solution required
- Must use permutation + used-array technique
- Limited global variables
- Exact output formatting required

---

## Build & Run

```bash
gcc main.c -Wno-unused-result -lm
./a.out
```

---

## Outcome

The final solution efficiently computes the optimal garage pairing and showcases how **AI-assisted optimization** can significantly improve the performance of recursive algorithms under strict academic constraints.
