---
aliases: [if and only if, biconditional, biconditional statement]
--- 

#logic 

## Definition 

> [!tldr] Definition
> A **biconditional statement** is a [[Propositions|proposition]] that has the form "$A$ if and only if $B$" where $A$ and $B$ are [[Atomic and molecular propositions|atomic statements]]. 
> 
> The biconditional statement  "$A$ if and only if $B$" is written in mathematical notation as $A \leftrightarrow B$. 

Notes:
* We consider the double arrow in $P \leftrightarrow Q$ to be a [[Connectives|connective]] that joins the [[Propositions|propositions]] $P$ and $Q$. 
* The [[Truth tables|truth table]] for the biconditional statement $P \leftrightarrow Q$ is: 

| $P$ | $Q$ | $P \leftrightarrow Q$ | 
| -- | -- | ---- |
| T | T | T | 
| T | F | F | 
| F | T | F | 
| F | F | T | 

- In other words, **biconditional statements are true whenever the two propositions have the same truth value**. 
- The statement $P \leftrightarrow Q$ is [[Logical equivalence|logically equivalent]] to the statement $(P \rightarrow Q) \wedge (Q \rightarrow P)$. That is, the biconditional statement is true if 

## Examples 

Here are examples of conditional statements with the hypothesis and conclusions indicated: 

| Statement                                                                  | Hypothesis           | Conclusion    |
| -------------------------------------------------------------------------- | -------------------- | ------------- |
| If Bob has pizza, he'll get sick.                                          | Bob has pizza        | Bob gets sick |
| If $x > 3$ then $x^2 > 9$.                                                 | $x > 3$              | $x^2 > 9$     |
| A running time longer than 3 minutes follows from the input being too big. | The input is too big | The running time is longer than 3 minutes              |

Note the last example shows that the hypothesis of the conditional statement doesn't have to appear at the first of the sentence; it is merely the condition that triggers the response, and this can be phrased in different ways.  