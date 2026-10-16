---
title: "Week 2: Setting up, and what \u201ccomputation\u201d means"
date: 2026-09-11 10:30
tags: [绪论, setup]
categories: [journal]
---

**Week 2 · 11 September 2026 · Data Structures (数据结构), Tsinghua University · XuetangX**

First real session with the course material — got everything set up and started the opening lectures.

<!-- more -->

## 1. What I worked on

Enrolled on XuetangX, registered on the Tsinghua online judge with the same email, and got g++ working locally with `-std=c++14`. Then watched 绪论 A — the videos on what "computation" actually means.

## 2. What was challenging, and how I handled it

The lecture content was unexpected. I came in expecting code and got rope computers and straightedge constructions. At first I wasn't sure where it was going, but by the end of the video I got the point: these are examples of "basic operations" in different computational models, and the whole idea of analysing algorithms depends on agreeing what counts as one step. It clicked when he showed that a straightedge can do addition — I'd never thought of geometry that way before.

The four properties of an algorithm — correctness, determinism, feasibility, finiteness — took some effort to keep straight. Feasibility means each step is actually doable; finiteness means it terminates. The Hailstone sequence was the example that made this stick: it's a perfectly valid program, every step is simple, but nobody can prove it always terminates, so it's not an algorithm. It's interesting that such a simple program is still an open problem in mathematics.

I also figured out the OJ registration — the account email has to match the XuetangX one for grades to sync. Caught that early by reading the instructions carefully.

## 3. How well I ran my own learning

**Self-score: 89**

I got through everything I planned and made a real effort to understand the concepts rather than just watching passively. I paused videos to think through the examples and made sure I could explain each of the four algorithm properties before moving on. Not 100 because I stuck to the planned material without exploring anything beyond it.

## 4. What I'll do differently next session

Front-load any admin or setup tasks so the full period goes to course content. 45 minutes is enough for two or three videos plus exercises if I use it well.

## Evidence

Registered on XuetangX and the OJ. Notes from 绪论 A on the four algorithm properties and the Hailstone example.
