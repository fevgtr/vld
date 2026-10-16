---
title: 'Week 3: How you measure an algorithm'
tags:
  - 绪论
categories:
  - journal
date: 2026-09-18 10:30:00
---

<!-- What I actually did this session -->


<!-- more -->

## What I worked on


## Where I got stuck


## What I'd do differently next time


## Next session


**Week 3 · 18 September 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

All theory this week — how to measure how good an algorithm is without actually running it.

<!-- more -->

## 1. What I worked on

绪论 B1: performance measurement, problem size, worst-case analysis, and the idealised computation model. Four videos and the associated exercises.

## 2. What was challenging, and how I handled it

The first thing that tripped me up was why you can't just time your code. I mean, I knew from competitive programming that the same code runs differently on different machines, but I hadn't thought about it formally. The answer is you count operations instead of seconds, which removes the hardware from the equation. Makes sense, but then you need to define what counts as an "operation," and that's where the idealised model comes in.

Writing cost as T(n) instead of a single number was the part that took a bit to get used to. For sorting, n is the number of elements; for multiplying two numbers, n is the number of digits. They're both called n but they measure completely different things, and the function T means something different in each case. I had to pause the video and think about that for a minute.

Worst-case analysis I actually found intuitive — in competitive programming you always think about the worst input because that's what gets you TLE. What I hadn't considered is that this is a deliberate *choice*, not an obvious truth. You could analyse the average case instead, and sometimes that's more useful, but worst-case is the default because it gives a guarantee. The course presented it as a modelling decision, which felt more honest than the way I'd been thinking about it.

The idealised model that ignores cache, word length, and memory speed still feels a bit hand-wavy. I get that you need to simplify to say anything general, but I'm not fully convinced that ignoring all hardware details doesn't sometimes give you the wrong answer in practice.

## 3. How well I ran my own learning

**Self-score: 89**

This was my most focused session so far. The content is conceptual and there's no code to write, which normally makes me zone out, but I stayed with it because I kept finding connections to things I already sort of knew from competitive programming. The gap between "sort of knowing" and actually understanding was bigger than I expected. Not 100 because I only watched and took notes — I didn't try to come up with my own examples or look ahead at what's next.

## 4. What I'll do differently next session

After each video, close the tab and try to restate the main idea in one sentence before moving on. This week I watched all four in a row and by the end I had to go back to the first one to remember the details.

## Evidence

Notes on T(n), worst-case vs average-case, and the idealised model. No OJ submissions yet — this section of the course is all conceptual.
