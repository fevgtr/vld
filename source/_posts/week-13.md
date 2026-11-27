---
title: "Week 13: Algorithm analysis and bubble sort"
date: 2026-11-27 10:30
tags: [ch1]
categories: [journal]
---

**Week 13 · 27 November 2026**

Summation formulas, and why bubble sort is O(n²).

<!-- more -->

## 1. What I worked on

Continued section D on algorithm analysis. D1-2 级数 covers the summation formulas that keep showing up in complexity proofs. D2-1 循环 is about analyzing loops by counting iterations. D2-2 非极端元素+起泡排序 introduces bubble sort as a first concrete sorting algorithm.

## 2. What was challenging, and how I handled it

D1-2 covers arithmetic and geometric series, power sums, and harmonic series. Knowing the closed forms matters because loop analysis keeps producing sums like 1 + 2 + ... + n, and recognizing that as n(n+1)/2 is what turns a loop into an O(n²) claim. I wrote out each formula and matched it to the loop patterns in D2-1.

Bubble sort in D2-2 was easy to follow. Its worst case is O(n²) because each pass does one fewer comparison, so the total is (n-1) + (n-2) + ... + 1, the same arithmetic sum from D1-2.

## 3. How well I ran my own learning

**Self-score: 100**

I watched D1-2 before D2-1 so the summation formulas were fresh when the loop analysis needed them.

## 4. What I'll do differently next session

Move further into section D and try to analyze a loop or algorithm on my own before the lecture gives the answer.

## Evidence

XuetangX watch history for D1-2 级数, D2-1 循环, and D2-2 非极端元素+起泡排序.
