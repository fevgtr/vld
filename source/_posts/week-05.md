---
title: "Week 5: Turing machines"
date: 2026-10-02 10:30
tags: [绪论]
categories: [journal]
---

**Week 5 · 2 October 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

Back after a two-week gap — last Friday was Mid-Autumn Festival, so no class on the 25th.

<!-- more -->

## 1. What I worked on

绪论 B2: the Turing machine model and a worked example of one running. Two videos plus tracing through the example on paper.

## 2. What was challenging, and how I handled it

The Turing machine components — tape, read/write head, alphabet, state set, transition function — are straightforward individually, but keeping track of all of them at once while tracing an execution took practice. A transition rule like (q, c) → (p, d, L/R) means "if you're in state q reading character c, write d, move left or right, and switch to state p." I found that writing it out in words like this helped me internalise it.

When I traced B2-2's example on paper, I initially read the transition table top-to-bottom like code. Once I switched to treating it as a lookup table — find your current (state, character) pair, read off what to do — everything clicked and I could trace the whole execution smoothly. That shift in how I was reading the table was the key insight of this session.

The bigger conceptual question is why Turing machines matter when nobody builds them. By the end of the second video I could see the point: it's about defining what "computable" means, so later the course can talk about whether a problem is solvable at all, not just how fast. It connects computation theory to the practical algorithm work coming up.

## 3. How well I ran my own learning

**Self-score: 89**

I engaged well with the material — traced the example on paper rather than just watching, caught my own misreading of the transition table and corrected it, and pushed through the more abstract parts until I understood why they matter. I also spent the first few minutes reviewing my notes from week 3 to reconnect with where I'd left off, which helped me get into the session faster. Not 100 because I stayed within the course material rather than exploring related ideas on my own.

## 4. What I'll do differently next session

Before class, spend ten minutes reviewing the previous session's notes. The two-week gap made it clear that a quick review at the start saves time overall. Also, I want to look ahead at what's next — B3 on the RAM model and then big-O notation — so I have context for where these concepts are leading.

## Evidence

Paper trace of the B2-2 Turing machine example. No OJ submissions — the Turing machine section is conceptual with written exercises.
