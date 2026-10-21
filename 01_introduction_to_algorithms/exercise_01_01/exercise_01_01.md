# Exercise 1.1 — Binary Search

## Introduction

Solution to Exercise 1.1 from the book *Grokking Algorithms, Second Edition*.

## Problem

The problem statement is omitted due to copyright. See Exercise 1.1 in the referenced book.

## Solution

At each step, binary search reduces the number of remaining candidates by half.

Given a sorted list of 128 names, the number of steps required to reduce the list to a single remaining name can be determined by repeatedly dividing the number of candidates by 2.

| Step | Remaining names |
| --- | --- |
| 0 | 128 |
| 1 | 64 |
| 2 | 32 |
| 3 | 16 |
| 4 | 8 |
| 5 | 4 |
| 6 | 2 |
| 7 | 1 |

## Answer

7 steps.

## References

Bhargava, A. Y. (2024). *Grokking algorithms: An illustrated guide for programmers and other curious people* (2nd ed.). Manning Publications.
