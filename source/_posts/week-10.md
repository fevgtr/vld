---
title: "Week 10: Big-O and efficiency"
date: 2026-11-06 10:30
tags: [ch1]
categories: [journal]
---

**Week 10 · 6 November 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

From counting operations to classifying how fast they grow.

<!-- more -->

## 1. What I worked on

渐进复杂度 (asymptotic complexity): C1-1 主流长远 on why only the dominant term matters as input grows, C1-2 大O记号 on the formal definition of Big-O notation, C2-1 高效解 on what counts as an efficient algorithm, and C2-2 有效解 on identifying polynomial complexity by dropping lower-order terms and focusing on the highest-degree term.

## 2. What was challenging, and how I handled it

Big-O notation looked simple at first: drop the lower-order terms, drop the constant. But the formal definition uses a pair of constants (c and n₀) that took some thought. Saying f(n) = O(g(n)) means there exist c > 0 and n₀ such that f(n) ≤ c·g(n) for all n ≥ n₀. That "for all n beyond some threshold" part is what 主流长远 sets up: short-run behavior does not matter, only the long-run trend.

I paused the C1-2 video at the examples and tried to pick c and n₀ myself before the lecture showed them.

## 3. How well I ran my own learning

**Self-score: 100**

I watched C1-1 first so the motivation was clear before the formalism in C1-2, and I worked through the Big-O examples on my own before checking.

## 4. What I'll do differently next session

Start applying Big-O to code I write, so estimating complexity becomes automatic.

## Evidence

XuetangX watch history for C1-1 主流长远, C1-2 大O记号, C2-1 高效解, and C2-2 有效解.
