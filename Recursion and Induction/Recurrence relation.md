---
aliases: [recurrence relation, recurrence relations, order]
--- 

#recursion-induction 

## Definition 

> [!tldr] Definition
> A **recurrence relation** is a formula that defines a sequence using a rule that gives the next term of the sequence terms of previously-computed terms of the sequence. The **order** of the recurrence relation refers to the number of steps backward needed to define the next term. 

Notes: 
- A [[Recursion|recursive]] definition of a sequence consists of two parts: A set of *initial conditions* that explicitly give early terms of the sequence, and a recurrence relation used to build later terms of the sequence from the initial ones. 
- A **solution** to a recurrence relation is a [[Closed formula|closed formula]] that gives all the terms of the sequence without using [[Recursion|recursion]]. 
## Examples 

- The [[Fibonacci sequence]] uses the recurrence relation $F_n = F_{n-1} + F_{n-2}$ which, in English, says that each term of the sequence is the sum of the previous two. Because it requires going back two steps, this is a *second-order* recurrence relation. To compute the Fibonacci sequence terms, we also need initial conditions, in this case $F_0 = 1$ and $F_1 = 1$. 
- The number of circles in step $n$ of the visual pattern below can be expressed with the recurrence relation $T_n = T_{n-1} + n$ if we start the index at $n=1$. In words, the number of circles in the next step is equal to the number of circles from the previous step, plus the actual number of the step. (For example in Step 5, 15 circles, the number of circles is the number of circles from Step 4 plus the number 5. In Step 6, there would be $15 + 6 = 21$ circles, and so on.) 
![[triangular-visual.png]]
- Suppose the sequence $a_n$ 
## Resources 

(video)

Other resources: 
- 

## Practice 
