# Exercise 1.4 — Phone Book Number Search Run Time

## Introduction

Solution to Exercise 1.4 from the book *Grokking Algorithms, Second Edition*.

## Problem

The problem statement is omitted due to copyright. See Exercise 1.4 in the referenced book.

## Solution

> **Definition:**  A phone book is a paper-based directory containing an alphabetical listing of people's names and their corresponding phone numbers.

A phone book is normally sorted alphabetically by name rather than by phone number. Therefore, binary search cannot be used to find a person's name when only their phone number is known.

Instead, we must use linear search, examining the entries one by one until the matching phone number is found or the entire phone book has been searched.

Linear search has a worst-case time complexity of `O(n)`, where `n` is the number of entries in the phone book.

## Answer

`O(n)`

## References

Bhargava, A. Y. (2024). *Grokking algorithms: An illustrated guide for programmers and other curious people* (2nd ed.). Manning Publications.

[← Previous](../exercise_01_03/exercise_01_03.md) | [Home](../../README.md) | [Next →](../exercise_01_05/exercise_01_05.md)
