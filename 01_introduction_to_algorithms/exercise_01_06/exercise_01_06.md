# Exercise 1.6 — Phone Book Reading A Entries Run Time

## Introduction

Solution to Exercise 1.6 from the book *Grokking Algorithms, Second Edition*.

## Problem

The problem statement is omitted due to copyright. See Exercise 1.6 in the referenced book.

## Solution

> **Definition:**  A phone book is a paper-based directory containing an alphabetical listing of people's names and their corresponding phone numbers.

A phone book is sorted alphabetically by name. Therefore, all entries beginning with the letter A are grouped together.

Assuming the names are evenly distributed across the 26 letters of the alphabet, approximately `n/26` entries would need to be read, where `n` is the total number of entries in the phone book.

Big O notation describes how the number of operations grows as the input size increases, ignoring constant multiplicative factors.

Since 26 is a constant, `O(n/26)` simplifies to `O(n)`.

Therefore, reading all phone numbers belonging to people whose names begin with A has linear time complexity.

## Answer

`O(n)`

## References

Bhargava, A. Y. (2024). *Grokking algorithms: An illustrated guide for programmers and other curious people* (2nd ed.). Manning Publications.

[← Previous](../exercise_01_05/exercise_01_05.md) | [Home](../../README.md) | [Next →](../exercise_01_07/exercise_01_07.md)
