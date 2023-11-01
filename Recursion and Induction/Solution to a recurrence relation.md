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

## Examples 

- The recurrence relation $a_0 = 3$ and $a_n = 2a_{n-1}$ when $n > 0$ produces the sequence $3, 6, 12, 24, 48, \dots$. This is a geometric sequence  has the solution $a(n) = 3 \cdot 2^n$. 


## Resources 

(video)

Other resources: 
- 

## Practice 
