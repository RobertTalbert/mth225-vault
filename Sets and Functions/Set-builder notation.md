---
aliases: [set-builder notation, set builder notation]
--- 

#sets-functions 

## Definition 

> [!tldr] Definition
> **Set-builder notation** is a way of writing a [[Set and set elements|set]] where the set is defined by the rules that its elements must satisfy in order to be [[Set and set elements|elements]] of the set. Set-builder notation has two forms: 
> 
> - ("*Domain/filter*") The universal set from which elements are selected is given first, then a [[Predicate|predicate]] that filters out all but the elements of the set. 
> - ("*Formula/domain*") A formula is given first, then a universal set on which the formula is applied. 
>   
>   Examples of each form are below. 

Note: 
- A closely related Python concept is the [list comprehension](https://www.w3schools.com/python/python_lists_comprehension.asp), where a list is defined in terms of rules and formulas rather than explicitly listing the elements. For example the list `[0,3,6,9]` is generated from the list comprehension `[x for x in range(10) if x % 3 == 0]`. This is equivalent to the set, in set-builder notation, of $\{x \in \{0,1,2,\dots,9\} \, : \, 3 \ \text{divides} \ x\}$. 

## Examples 

- Domain/filter: The set $\{ x \in \mathbb{N} \, : \, x^2 < 100 \}$ takes the natural numbers as its universal set (or "domain") and filters out everything except those natural numbers whose square is less than 100. In roster notation, this set is equal to $\{0,1,2,3,4,5,6,7,8,9\}$. This way of writing a set is helpful when you are selecting elements from a larger group using rules that can be expressed through predicates. 
- Domain/filter: The set $\{a \in \mathbb{Z} \, : \, |a| \leq 1 \}$ is the set $\{-1, 0, 1\}$. 
- Formula/domain: The set $\{x^2 \, : \, x \in \mathbb{N}\}$ takes the formula $x^2$ and "maps" it over the set of all natural numbers. The resulting set in roster notation is $\{0, 1, 4, 9, 16, 25, 36, 49, \dots \}$. This way of writing a set is helpful when the elements of the set can be easily expressed through mathematical computations or constructions. 
- Formula/domain: The set $\{(t, t+1) \, : \ t \in \mathbb{N}\}$ takes each natural number and creates a pair with the natural number in the first coordinate and the next natural number in the second coordinate. It is equal to the set $\{(0,1), (1,2), (2,3), (3,4), \dots \}$. 


## Resources 

(video)

Other resources: 
- 

## Practice 
