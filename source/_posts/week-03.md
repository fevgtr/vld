---
title: "Week 3: How you measure an algorithm"
date: 2026-09-18 10:30
tags: [绪论]
categories: [journal]
---

**Week 3 · 18 September 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

All theory this week — how to measure how good an algorithm is without actually running it.

<!-- more -->

## 1. What I worked on

绪论 B1: performance measurement, problem size, worst-case analysis, and the idealised computation model. Four videos and the associated exercises.

## 2. What was challenging, and how I handled it

The first concept that took real thought was why you can't just time your code. I knew from competitive programming that the same code runs differently on different machines, but I hadn't framed it formally before. The answer is you count operations instead of seconds, which removes the hardware from the equation — and then you need to define what counts as an "operation," which is where the idealised model comes in.

Writing cost as T(n) instead of a single number took a moment to get used to. For sorting, n is the number of elements; for multiplying two numbers, n is the number of digits. They're both called n but they measure completely different things, and the function T means something different in each case. I paused the video and worked through this with my own examples until it felt natural.

Worst-case analysis I actually found intuitive — in competitive programming you always think about the worst input because that's what gets you TLE. What the course added was framing this as a deliberate *choice*: you could analyse the average case instead, and sometimes that's more useful, but worst-case is the default because it gives a guarantee. Seeing it presented as a modelling decision connected the formal theory to the practical intuition I already had, which was satisfying.

The idealised model that abstracts away cache, word length, and memory speed made me think about when simplifications are useful versus when they hide something important. The course's argument — that you need to abstract to say anything general — is convincing, and I can see how it connects to big-O notation coming up next.

## 3. How well I ran my own learning

**Self-score: 89**

This was my most focused session so far. The content is conceptual with no code to write, which can be harder to stay engaged with, but I kept finding connections to things I already knew from competitive programming. The gap between "sort of knowing" and formally understanding was bigger than I expected, and closing that gap felt productive. Not 100 because I followed the planned sequence without looking ahead or generating my own examples beyond what the exercises asked for.

## 4. What I'll do differently next session

After each video, close the tab and restate the main idea in one sentence before moving on. This helps me check whether I actually understood it or just followed along.

## Evidence

Notes on T(n), worst-case vs average-case, and the idealised model. No OJ submissions — this section of the course is all conceptual with written exercises.
