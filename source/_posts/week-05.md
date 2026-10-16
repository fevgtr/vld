---
title: 'Week 5: Turing machines'
tags:
  - 绪论
categories:
  - journal
date: 2026-10-02 10:30:00
---

<!-- What I actually did this session -->


<!-- more -->

## What I worked on


## Where I got stuck


## What I'd do differently next time


## Next session


**Week 5 · 2 October 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

Back after a two-week gap — last Friday was Mid-Autumn Festival, so no class on the 25th.

<!-- more -->

## 1. What I worked on

绪论 B2: the Turing machine model and a worked example of one running. Two videos plus tracing through the example on paper.

## 2. What was challenging, and how I handled it

Coming back after two weeks off was rough. I couldn't remember where I'd left off and spent the first few minutes scrolling through my notes from week 3. I hadn't looked at any course material during the break, which is exactly the kind of thing that shows whether you're self-directing or just following a schedule. I was following the schedule.

The Turing machine itself: tape, read/write head, alphabet, state set, transition function. I can list those now, but during the video I kept forgetting the transition function. A rule like (q, c) → (p, d, L/R) means "if you're in state q reading character c, write d, move left or right, and switch to state p." It makes sense when you read it, but when I tried to trace B2-2's example on paper I kept losing track of which state I was in after each step. I think I was reading the transition table as a sequence of instructions — top to bottom, like code — instead of as a lookup table where you find your current (state, character) pair. Once I started treating it as a lookup table it went much smoother.

The bigger question is why any of this matters. Nobody builds Turing machines. The course spends two full videos on them, and I'll be honest: during the first video I thought it was a detour. By the end of the second I think I see the point — it's about defining what "computable" means so you can later say whether a problem is solvable at all, not just slowly. But I'm not fully there yet. I'll see if it connects to something later.

## 3. How well I ran my own learning

**Self-score: 79**

I showed up and did the work, but the two-week break exposed that I'm not doing anything outside of class time. I didn't review, didn't look ahead, didn't try anything on my own during the holiday. That's "working within structure." The session itself was fine — I traced the example, caught my own mistake with the transition table, and pushed through the parts I didn't immediately see the point of. But the overall pattern is still reactive.

## 4. What I'll do differently next session

Before class, spend ten minutes reviewing last session's notes. The two-week gap made it obvious that I forget everything between sessions if I don't look at it at all. Also: I'm four sessions in and still in Chapter 1. The pace isn't a problem by itself — the course site says slow is fine — but I want to at least know what's ahead so I'm not surprised.

## Evidence

Paper trace of the B2-2 Turing machine example (not photographed). No OJ submissions — the Turing machine section doesn't have programming exercises.
