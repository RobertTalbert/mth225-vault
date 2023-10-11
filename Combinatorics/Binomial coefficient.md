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

## Examples 

- Because $\displaystyle{\binom{n}{k}}$ is the number of ways to select $k$ objects from a group of $n$ objects, $\displaystyle{\binom{5}{5}} = 1$. There is only one way to take a group of 5 objects and select all 5. The closed formula above also says this, but remember the binomial coefficient solves a counting problem. 
- More generally, $\displaystyle{\binom{n}{n}} = 1$ for all $n \geq 0$. 
- For the same reason, $\displaystyle{\binom{n}{0}} = 1$ for any $n \geq 0$ because there is only one way to select nothing from a group of $n$ objects. 
- **How many ways are there to choose three letters from the alphabet A..Z without duplication?** This question

## Resources 

(video)

Other resources: 
- 

## Practice 
