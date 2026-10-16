---
title: "Week 1: Picking the course took longer than I thought it would"
date: 2026-09-04 10:30
tags: [planning, course selection]
categories: [journal]
---

I spent this session actually deciding what my VLD is going to be, instead of circling it. The direction was never really in question — data structures and algorithms, written in C++ — but *which* course turned out to be a real decision.

<!-- more -->

## What I was choosing between

I had four serious options:

- **Stanford CS106B.** All the lectures, assignments and handouts are public, and
  it's taught in C++. Problem: nothing I submit gets marked. I'd be writing code
  into a void and guessing whether it was right.
- **UC San Diego's Data Structures specialisation** on Coursera. Properly graded,
  but it costs money unless I apply for financial aid, which is two essays and a
  couple of weeks of waiting. It also mixes Python, Java and C++.
- **UIUC's Accelerated CS Fundamentals**, also Coursera, also C++, free to audit.
  Closest to a drop-in answer. But it's about 60 hours total across three courses,
  and it assumes you already know a language and want the C++ version of what you
  know. Shallow for a whole year.
- **Tsinghua's 数据结构**, taught by Prof. Deng Junhui, free on XuetangX.

## What I went with, and why

Tsinghua. Three reasons, in order of how much they actually mattered:

1. **The work gets graded.** There's a real online judge at
   `dsa.cs.tsinghua.edu.cn/oj` that compiles and runs my submissions against
   hidden test cases. 6 problem sets and 4 programming assignments. If my code is
   wrong I find out, which is the whole difference between studying and just
   reading.
2. **It's entirely C++, and it's C++ I don't write.** The course is built around
   templated container classes — the kind of code where you implement `Vector`
   yourself and then have to argue about why insertion is O(n). I've written a lot
   of C++ for contests, but contest C++ is loops and arrays. I've basically never
   written a class template.
3. **It's free, permanently.** No aid application, no audit-mode restrictions, no
   deadline I can miss.

The catch is that it's hard. It's the course Tsinghua's CS department actually
runs, not a MOOC adaptation of one, and the prerequisites list inheritance,
virtual methods, templates, induction and expected value. I'm shaky on at least
half of that.

## The thing I almost got wrong

My first instinct was to skip the course entirely and just grind problems —
USACO Guide, CSES, Codeforces EDU. It's tempting because you get a green tick
every twenty minutes and it feels like progress.

I talked myself out of it. Problem sets teach you to recognise patterns you've
already seen. They don't teach you *why* a balanced tree is balanced, and I'd
have spent a year getting faster at things I already half-know. The whole reason
VLD is a year long is so I can learn something that doesn't fit in a weekend.

That said, I think I was also avoiding the course because it's intimidating. Worth
being honest about that, because it'll probably come back when I hit the part of
the course I don't understand.

## Next

- Get this approved by Mr. Wright before I enrol.
- Enrol in Part 1 and register on the judge with the same email so grades sync.
- Check my C++ prerequisites honestly — specifically templates, which I suspect
  I'll need to go back and learn properly before Chapter 2.
