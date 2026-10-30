---
title: "Week 9: The RAM model"
date: 2026-10-30 10:30
tags: [ch1]
categories: [journal]
---

**Week 9 · 30 October 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

Moving past Turing machines to a computation model closer to real hardware.

<!-- more -->

## 1. What I worked on

绪论 B3: the RAM (Random Access Machine) model and worked examples. B3-1 covered the model itself, B3-2 applied it to concrete problems. Also finished the 01B 计算模型 assignment and watched the video explanation for it.

## 2. What was challenging, and how I handled it

The jump from Turing machines to RAM felt big at first. A Turing machine reads one cell at a time and shuffles left or right. A RAM can reach any memory address in one step. In the Turing model, just reading the input is already O(n) because each cell takes a step to reach. In the RAM model, memory access, comparison, and arithmetic all cost O(1), so you count how many of those operations your code uses.

I followed the B3-2 examples along with the lecture, pausing to count the operations myself before the video showed the answer.

## 3. How well I ran my own learning

**Self-score: 100**

I reviewed my B2 notes before starting so the comparison made sense, and I finished the 01B assignment on my own before watching the explanation video.

## 4. What I'll do differently next session

Start using the RAM model to estimate costs of simple code I write, so the counting becomes automatic.

## Evidence

XuetangX watch history for B3-1 and B3-2. Completed 01B 计算模型 assignment and its video explanation.
