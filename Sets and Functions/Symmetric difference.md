---
aliases: [symmetric difference]
--- 

#sets-functions 

## Definition 

> [!tldr] Definition
> If $A$ and $B$ are [[Set|sets]], the **symmetric difference** of $A$ and $B$ is the set whose [[Set|elements]] are all the elements that are in either $A$ or $B$, but not in both. In notation, the symmetric difference of $A$ and $B$ is written $A \triangle B$. In [[Set-builder notation|set-builder notation]], 
> $$A \triangle B = \{ x \, : \, x \in A \cup B \ \text{and} \ x \not \in A \cap B\}$$

A visual representation of $A \triangle B$ is this Venn diagram: 
![[Pasted image 20230927084845.png|300]]
Image credit: https://www.javatpoint.com/symmetric-difference-between-two-sets

**Notes:**
- We can also define $A \triangle B$ as the [[Set difference|set difference]] between the [[Union|union]] of $A$ and $B$, and the [[Intersection|intersection]] of $A$ and $B$: $A \triangle B = (A \cup B) \setminus (A \cap B)$. 
- The symmetric difference is the set-theory equivalent of the [[Exclusive OR|exclusive or]] operation in logic, and sometimes the same notation is used to denote it: $A \oplus B$. 
## Examples 

- If $A = \{1,2,3,4\}$ and $B = \{1,3,5,7,9\}$ then $A \triangle B = \{1,2,4,5,7,9\}$. That is, the symmetric difference is all elements of $A \cup B$ except $3$ since $3$ is in both sets. 
- If $A = \{n \in \mathbb{N} \, : \, n \ \text{is odd and greater than 3}\}$ and $B =  \{n \in \mathbb{N}  \, : \, n \ \text{is even and greater than 3}\}$ then $A \triangle B = \{4,5,6,7,8,\dots\}$, which in this case is the same as $A \cup B$ since $A$ and $B$ are [[Intersection|disjoint]] (because a natural number greater than 3 cannot be odd and even at the same time). 

## Resources 

(video)

Other resources: 
- 

## Practice 
