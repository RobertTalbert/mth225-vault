---
aliases: [cartesian product]
--- 

#sets-functions 

## Definition 

> [!tldr] Definition
> If $A$ and $B$ are [[sets]], the **Cartesian product** of $A$ and $B$ is the set of all ordered pairs whose first coordinate is an [[Set|element]] of $A$ and whose second coordinate is an element of $B$. In notation, the Cartesian product of $A$ and $B$ is written $A \times B$. In [[Set-builder notation|set-builder notation]], 
> $$A \times B = \{ (x,y) \, : \, x \in A \ \text{and} \ y \in B\}$$

**Notes:**
- The symbol $\times$ does *not* mean "multiplication" in this context. 
- The order of sets in a Cartesian product matters: $A \times B$ is not the same set as $B \times A$ because the pairs in the Cartesian product are *ordered* pairs -- switching coordinates does not keep the ordered pairs equal. 
- In Python terminology, the elements of a Cartesian product are [tuples](https://www.w3schools.com/python/python_tuples.asp) with two elements. 
- It is possible to similarly define the Cartesian product of more than two sets, using tuples that have more than two elements. For example $A \times B \times C$ would be the set of all three-element tuples with the first coordinate in $A$, the second in $B$, and the third in $C$. 
- If $A$ is a finite set with [[Cardinality|cardinality]] equal to $N$, and $B$ is finite with cardinality $M$, then $A \times B$ has cardinality $N \cdot M$ since $A \times B$ contains all the combinations of elements from $A$ and $B$. 

## Examples 

* Let $A = \{0,1,2\}$ and $B = \{s,t\}$. Then $A \times B = \{(0,s), (0,t), (1,s), (1,t), (2,s), (2,t)\}$. 
* Let $S = \{x,y,z\}$. Then $S \times S$ is the set of all ordered pairs whose coordinates from from $S$: $\{(x,x), (x,y), (x,z), (y,x), (y,y), (y,z), (z,x), (z,y), (z,z)\}$. 
* We can also find the Cartesian product of infinite sets. For example, if $S$ = \{x,y,z\} and $\mathbb{N}$ is thj

## Resources 

(video)

Other resources: 
- 

## Practice 
