---
aliases: [solution, solution to a recurrence relation]
--- 

#recursion-induction 

## Definition 

> [!tldr] Definition
> A **solution** to a [[Recurrence relation|recurrence relation]] is a [[Closed formula|closed formula]] that produces the same sequence of objects that the recurrence relation produces. 

Notes: 
- Whereas a recurrence relation produces objects in a sequence [[Recursion|recursively]], a solution to the recurrence relation produces them directly. 
- Solutions to recurrence relations are useful for making computations but are not always preferable to recursion, since they can hide key insights on the structure of the objects in the sequence. 
- There are numerous methods for finding solutions to recurrence relations, including the [[characteristic root method]] if the recurrence relation is linear and homogeneous, as well as the basic methods for finding solutions if the sequence is an [[Arithmetic sequence|arithmetic]] or [[Geometric sequence|geometric]] sequence of numbers. 
- Taking a given closed formula and checking that it is indeed a solution to a recurrence relation, involves a proof using [[Mathematical induction|mathematical induction]]. 

## Examples and Non-Examples 

- The recurrence relation $a_0 = 3$ and $a_n = 2a_{n-1}$ when $n > 0$ produces the sequence $3, 6, 12, 24, 48, \dots$. This is a geometric sequence that has the solution $a(n) = 3 \cdot 2^n$. 
- The sequence $1, 3, 6, 10, 15, \dots$ given by the recurrence relation $T_1 = 1$ and $T_n = T_{n-1} + n$ when $n > 1$, has a solution given by $T(n) = \dfrac{n(n+1)}{2}$. 
- The [[Fibonacci sequence]] $1, 1, 2, 3, 5, 8, 13, 21, \dots$ given by the recurrence relation $F_1 = 1, F_2 = 1$ and $F_n = F_{n-1} + F_{n-2}$ when $n > 2$ has the solution: 
$$F_n = \frac{\left(\frac{1+\sqrt{5}}{2}\right)^n - \left(\frac{1-\sqrt{5}}{2}\right)^n}{\sqrt{5}}$$
- **Non-example:** Consider the recurrence relation: $a_0 = 2$, $a_1=5$, and for $n > 1$, $a_n = 3a_{n-1} - 2a_{n-2}$.  This produces the sequence $2, 5, 11, 23, 47, 95, ...$ The function $a(n) = 1.5n^2 + 1.5n + 2$ is *not* a solution to this recurrence relation. It produces the first three terms correctly: $a(0) = 2, a(1) = 5, a(2) = 11$. But then whereas the fourth term ($n=3$) of the sequence is $23$, the formula instead gives $a(3) = 1.5 \cdot 3^2  1.5 \cdot 3 + 2 = 20$. 

Just because a formula produces the first few terms of a seque

## Resources 

(video)

Other resources: 
- 

## Practice 
