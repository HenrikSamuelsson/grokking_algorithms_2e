# Exercise 1.5 — Phone Book Reading All Entries Run Time

## Introduction

Solution to Exercise 1.5 from the book *Grokking Algorithms, Second Edition*.

## Problem

The problem statement is omitted due to copyright. See Exercise 1.4 in the referenced book.

## Solution

> **Definition:**  A phone book is a paper-based directory containing an alphabetical listing of people's names and their corresponding phone numbers.

The time required to read every phone number in a phone book grows linearly with the number of entries.

Since every entry must be examined exactly once, the number of operations is proportional to the number of entries.

Therefore, reading every phone number has a time complexity of `O(n)`, where `n` is the number of entries in the phone book.

## Answer

`O(n)`

## References

Bhargava, A. Y. (2024). *Grokking algorithms: An illustrated guide for programmers and other curious people* (2nd ed.). Manning Publications.

[← Previous](../exercise_01_04/exercise_01_04.md) | [Home](../../README.md) | [Next →](../exercise_01_06/exercise_01_06.md)
