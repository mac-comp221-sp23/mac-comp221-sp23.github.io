---
layout: post
title:  "Activity 12: More Divide \& Conquer Design"
categories: Activity DivideAndConquer Design
---

## Learning Goals

You will work towards being able to...

1. Use divide and conquer design principles to write algorithms to solve problems


## Instructions
Work with your groups on the following problems:

1. (Skiena 5-2) Suppose you have a sorted array of size $n$ that contains the integers $1 \dots n + 1$ with one element missing. Write an algorithm (in $O(\log n)$ worst case time) to find that integer.

**Hint**: $\log n$ time tells us we can cut down out search space by a fraction each time we run some check. Looking mighty-like Binary Search!

2. (Skiena 5-5) Suppose you have a sorted array of *distinct integers* $A$. Find a $O(\log n) algorithm find whether there exists some index $i$ such that $A[i] = i$. 

**Hint**: Remember that the array is sorted and contains *integers*. This means that $A[i+1] \geq 1 + A[i]$! for any index $1 \leq i < N$!

#### Submission
Submit an artifact of your work for problem 1 or 2.
