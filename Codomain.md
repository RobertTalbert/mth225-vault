---
aliases: [codomain]
--- 

#sets-functions 

## Definition 

> [!tldr] Definition
> The **codomain** of a [[Function|function]] is the set consisting of all allowable outputs of that function. In standard function notation, if $f: A \rightarrow B$ is a function then the set $B$ is the codomain. 

Notes: 
- The codomain of $f$ contains the [[Range|range]] of the function as a [[Subset|subset]], but the two are not necessarily equal. See examples below. 
- Informally we can think of the codomain as specifying the "data type" of the outputs. For example the ceiling function $ceil: \mathbb{R} \rightarrow \mathbb{Z}$ that takes a real number and rounds it up, has a codomain of $\mathbb{Z}$ which indicates that the outputs are of "type integer". 

## Examples 

- The function $f: \mathbb{R} \rightarrow \mathbb{R}$ defined as the formula $f(x) = x^2$ has codomain equal to $\mathbb{R}$, the set of all real numbers. (This is also its [[Domain|domain]].)
- The function $p: \mathbb{N} \rightarrow \mathbb{N}$ defined by assigning $n$ to the $n$th digit of $\pi$. So $p(0) = 3$, $p(1) = 1$, $p(2) = 4$, $p(3) = 1$, etc. has codomain equal to the natural numbers (same as its domain). 
- The function from $A = \{-2,0,3,5\}$ to $B = \{-4,-3,4\}$ shown in the diagram below has a codomain of $\{-4,-3,4\}$: 
- The function shown below takes a positive integer and returns a list of all of its positive divisors. For example `divisors(18) = [1,2,3,6,9,18]`. The domain in this case is the set of all positive integers, and the codomain is the set of all *lists of* positive integers. (That is, the outputs have a "data type" of lists containing positive integers.)
```python

```

## Resources 

(video)

Other resources: 
- 

## Practice 
