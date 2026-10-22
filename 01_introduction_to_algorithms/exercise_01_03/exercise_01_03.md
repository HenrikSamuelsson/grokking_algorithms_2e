# Exercise 1.3 — Phone Book Search Run Time

## Introduction

Solution to Exercise 1.3 from the book *Grokking Algorithms, Second Edition*.

## Problem

The problem statement is omitted due to copyright. See Exercise 1.3 in the referenced book.

## Solution

> **Definition:**  A phone book is a paper-based directory containing an alphabetical listing of people's names and their corresponding phone numbers.

Printed phone books have largely been replaced by digital directories, but the underlying search principles remain applicable.

A fast way to locate a person's phone number in a phone book is to use binary search.

Start by opening the phone book approximately in the middle. Compare the name on the current page with the name being searched for. Based on their alphabetical ordering, discard the half of the remaining entries that cannot contain the requested name.

Continue by repeatedly dividing the remaining entries in half until the requested name is found or no entries remain.

Binary search has a worst-case time complexity of `O(log n)`, where n is the number of entries in the phone book. Therefore, the phone number can be found in logarithmic time.

## Answer

`O(log n)`

## References

Bhargava, A. Y. (2024). *Grokking algorithms: An illustrated guide for programmers and other curious people* (2nd ed.). Manning Publications.

[← Previous](../exercise_01_02/exercise_01_02.md) | [Home](../../README.md) | [Next →](../exercise_01_04/exercise_01_04.md)
