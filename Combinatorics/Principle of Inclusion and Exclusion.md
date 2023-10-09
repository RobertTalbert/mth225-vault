---
aliases: [Inclusion-Exclusion Principle, Inclusion-Exclusion, PIE]
--- 

#combinatorics 

## Definition 

> [!tldr] Definition
> The Principle of Inclusion and Exclusion states that if an event $A$ can occur in $m$ ways, and an event $B$ can occur in $n$ ways, and there are $p$ ways for both $A$ and $B$ to happen at the same time, then the number of ways for the event "$A$ or $B$" to happen is $m+n-p$. 

Notes: 
- Informally the Principle of Inclusion and Exclusion says that the number of ways for either $A$ or $B$ to happen equals the number of ways $A$ can happen, plus the number of ways $B$ can happen, **minus the number of ways $A$ and $B$ can happen**. 
- The subtraction is due to the fact that outcomes where $A$ and $B$ happen simultaneously are counted twice if we just add the outcomes of $A$ to the outcomes of $B$. 
- The Principle of Inclusion and Exclusion can be phrased in terms of [[Set|sets]]: If $A$ and $B$ are any two sets, then $|A \cup B| = |A| + |B| - |A \cap B|$. (The vertical bars indicate [[Cardinality|cardinality]]; the symbol $\cup$ is the [[Union|union]]; the symbol $\cap$ is [[Intersection|intersection]].)
- The Principle of Inclusion and Exclusion can be extended to three or more events, but the formula gets progressively more complicated. [Go here to learn more](https://artofproblemsolving.com/wiki/index.php/Principle_of_Inclusion-Exclusion#Three_Set_Examples). 

## Examples and Non-Examples



## Resources 

(video)

Other resources: 
- Tutorial: [Principle of Inclusion-Exclusion](https://artofproblemsolving.com/wiki/index.php/Principle_of_Inclusion-Exclusion)

## Practice 
