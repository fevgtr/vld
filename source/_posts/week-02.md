---
title: 'Week 2: Setting up, and what “computation” means'
tags:
  - 绪论
  - setup
categories:
  - journal
date: 2026-09-11 10:30:00
---

<!-- What I actually did this session -->


<!-- more -->

## What I worked on


## Where I got stuck


## What I'd do differently next time


## Next session


**Week 2 · 11 September 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

First real session with the course material. Half of it was setup, the other half was the opening lectures on computation.

<!-- more -->

## 1. What I worked on

Enrolled on XuetangX, registered on the Tsinghua online judge with the same email, and got g++ working locally with `-std=c++14`. Then watched 绪论 A — the videos on what "computation" actually means.

## 2. What was challenging, and how I handled it

Setting up the OJ took longer than it should have. I didn't realise the account email had to match the XuetangX one, so I registered with the wrong email first and had to redo it. Not hard, just annoying — and it's the kind of thing I should have read the instructions for before clicking.

The lecture content was unexpected. I came in expecting code and got rope computers and straightedge constructions. My first reaction was "why am I watching this," but by the end of the video I got the point: these are examples of "basic operations" in different computational models, and the whole idea of analysing algorithms depends on agreeing what counts as one step. It clicked when he showed that a straightedge can do addition, because I'd never thought of geometry that way.

The four properties of an algorithm — correctness, determinism, feasibility, finiteness — I can list them now, but during the video I kept mixing up feasibility and finiteness. Feasibility means each step is actually doable; finiteness means it stops. The Hailstone sequence was the example that made this stick: it's a perfectly valid program, it runs, every step is simple, but nobody can prove it always terminates, so it's not an algorithm. I thought the distinction was a bit academic at first, but it's actually kind of interesting that such a simple program is an open problem.

## 3. How well I ran my own learning

**Self-score: 89**

I got through everything I planned and made a real attempt to understand the concepts rather than just watching. But I spent the first twenty minutes on setup that I could have done at home the night before. If I'd done that, I would have had time to try the first OJ problem. Managing my learning, not directing it yet.

## 4. What I'll do differently next session

Do any setup or admin stuff outside class time. The period is only 45 minutes — that's two or three videos plus exercises if I don't waste any of it.

## Evidence

Registered on XuetangX and the OJ (no screenshots taken at the time). Notes from 绪论 A on the four algorithm properties and the Hailstone example.
