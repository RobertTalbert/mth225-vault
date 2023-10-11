---
aliases: [binomial coefficient]
--- 

#combinatorics 

## Definition 

> [!tldr] Definition
> For each [[Integers|integer]] $n \geq 0$ and for each integer $k$ with $0 \leq k \leq n$, the **binomial coefficient**, denoted $\displaystyle{\binom{n}{k}}$ and pronounced "$n$ choose $k$", is a number that represents the number of ways to select $k$ objects from a group of $n$ distinct objects. 

**Notes:**

- Please note, $\binom{n}{k}$ is *not* a fraction. For example $\binom{10}{2}$ does not equal $5$. 
- The binomial coefficient $\binom{n}{k}$ also represents: 
	- The number of [[Binary digits and bitstrings|bitstrings]] with length $n$ and [[Weight of a bitstring|weight]] $k$ 
	- The number of $k$-element [[Subset|subsets]] of an $n$-element set 
	- The coefficient on $x^ky^{n-k}$ in the expansion of $(x+y)^n$
- The binomial coefficient $\binom{n}{k}$ can be computed [[Recursion|recursively]] when $n \geq 1$ and $k \geq 1$, using the [[Recurrence relation|recurrence relation]]: 
$$\binom{n}{k} = \binom{n-1}{k-1} + \binom{n-1}{k}$$
- The binomial coefficient $\binom{n}{k}$ can be computed directly using the closed formula
$$\binom{n}{k} = \frac{n!}{k! (n-k)!}$$
Here, the exclamation point in $n!$ is the [[Factorial|factorial function]]. 

## Examples and Non-Examples

## Resources 

(video)

Other resources: 
- 

## Practice 
