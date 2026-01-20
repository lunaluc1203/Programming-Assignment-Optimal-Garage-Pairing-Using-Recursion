Optimal Garage Pairing Using Recursion

A C program that computes the minimum total distance required to connect garages using expressways. This project emphasizes recursive optimization and demonstrates how AI tools were used to improve performance for larger inputs.

Project Overview

Given the coordinates of 2n garages, the program pairs them into n expressways such that each garage is used exactly once and the total distance is minimized. The solution explores all valid pairings using a recursive permutation approach.

AI-Assisted Optimization

This assignment required the use of AI tools to optimize the program for higher values of n.

The initial implementation worked correctly for smaller inputs. AI assistance (ChatGPT) was used to identify performance bottlenecks and introduce early pruning, allowing the recursion to terminate branches when partial distances exceeded the current best solution. This significantly improved runtime while preserving the required recursive structure.

Key Features

Recursive permutation generation using a used[] array

Early pruning to reduce unnecessary recursion

Euclidean distance calculations between garage coordinates

Deterministic and precisely formatted output

Improved performance for larger input sizes

Technical Skills Demonstrated

C Programming

Recursion and Backtracking

Permutation Algorithms

Algorithm Optimization

AI-Assisted Problem Solving

Dynamic Memory Management

Floating-Point Precision Handling

Algorithm Summary

The program recursively generates permutations of garage indices, forms garage pairs sequentially, accumulates distances as pairs are created, and prunes branches early when they exceed the best known distance. The optimal pairing is stored and printed.

Constraints

No file input/output

Recursive solution required

Permutation with used-array technique enforced

Limited global variables

Exact output formatting required

Build and Run

gcc main.c -Wno-unused-result -lm
./a.out

Outcome

The final solution efficiently computes the minimum expressway distance and demonstrates effective use of AI to optimize a recursive algorithm under strict academic constraints.
