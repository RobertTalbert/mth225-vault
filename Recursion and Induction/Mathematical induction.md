---
aliases: [induction, mathematical induction, Induction, inductive hypothesis]
--- 

#recursion-induction 

## Definition 

> [!tldr] Definition
> **Mathematical induction** is a [[proof]] technique used when proving that a [[Predicate|predicate]] $P(n)$ (whose [[Domain|domain]] is the set of all [[Natural numbers|natural numbers]]) is true for all natural numbers or for some specified [[Subset|subset]]. It is especially applicable if the predicate involves [[Recursion|recursion]]. Induction proofs follow a three-step **framework**: 
> 1. (*Base case*) Establish, by direct computation or demonstration, that $P(n)$ is true for the smallest value of $n$ for which it is claimed to be true. That is, establish that the base case leads to a true statement.  
> 2. (*Inductive hypothesis*) Assume that $P(k)$ is true for some random, undisclosed value of $k$. 
> 3. (*Inductive step*) Prove that $P(k+1)$ is true, using a combination of the inductive hypothesis, the recursion involved in the predicate, previously-proven results, and so on. 

**Notes**: 
- This general framework is sometimes known as *weak induction*. Other forms of induction are possible, including [strong induction](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/resources/lecture-3-strong-induction/), [structural induction](https://www.cs.umd.edu/class/summer2016/cmsc250/files/slides/structuralInduction.pdf), and [transfinite induction](https://mathworld.wolfram.com/TransfiniteInduction.html). 
- The base case is often $n = 0$ but not always. Check the statement being proven for the smallest case.

## Examples 




Here are two examples of proof by mathematical induction: 

> [!NOTE] **Claim:** For all natural numbers $n$, the number $n^3 + 2n$ is divisible by $3$. 
> 
> **Proof:** First, to prove the base case, if $n=0$ then we have $0^3 + 2(0)$ which equals $0$. This is a multiple of $3$ because $0 = 3 \times 0$. Therefore the base case is proven. 
> 
> Now assume that for some natural number $k$, $k^3 + 2k$ is a multiple of 3. We want to show that $(k+1)^3 + 2(k+1)$ is a multiple of 3. Expand this out to get: 
> 
> $$\begin{align}
> (k+1)^3 + 2(k+1) &= (k^3 + 3k^2 + 3k + 1) + (2k + 2) \\
>    &= (k^3 + 2k) + 3k^2 + 3k + 3
> \end{align}
> $$
> Now we already assumed that $k^3 + 2k$ was a multiple of 3, and clearly the last three terms are multiples of 3 because 3 is a factor on each. Therefore $(k+1)^3 + 2(k+1)$ is a sum of multiples of 3, which makes the entire expression a multiple of 3. 
> 
> That ends the proof.   

## Resources 

(video)

Other resources: 
- 

## Practice 
