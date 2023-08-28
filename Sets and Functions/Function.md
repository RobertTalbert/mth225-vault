---
aliases: [functions, function]
--- 

#sets-functions 

## Definition 

> [!tldr] Definition
> A **function** is a rule that accepts input from one set and produces output in another set, so that every input is assigned to one and only one output. If the inputs come from from the set $A$ and the outputs come from the set $B$, and the name of the function is $f$, then we write $f: A \rightarrow B$. 

Notes: 
- In the notation above ($f: A \rightarrow B$) the set $A$ is the [[Domain|domain]] of the function and the set $B$ is the [[Codomain]]. 
- If $x \in A$, then the output that is assigned to $x$ by the function $f$ is notated $f(x)$ ("f of x"). This is sometimes called the *image* of $x$.
- Functions can take on different forms or representations. Common forms are: 
	- *Formulas*. For example $f: \mathbb{Z} \rightarrow \mathbb{Z}$ defined by $f(n) = 2n$ is a function that assigns each integer input $n$ to its double. 
	- *Tables or lists*. For example $g: \{0,1,2\} \rightarrow \{a,b,c\}$ defined by $g(0) = c$, $g(1) = a$, $g(2) = b$ is a function, defined by explicitly listing the outputs assigned to each input. 
	- *Verbal descriptions.* For example, define the function $p: \mathbb{N} \rightarrow \mathbb{N}$ by assigning $n$ to the $n$th digit of $\pi$. So $p(0) = 3$, $p(1) = 1$, $p(2) = 4$, $p(3) = 1$, etc. 
	- *Graphs or diagrams*. For example the diagram below defines a function from $A = \{-2,0,3,5\}$ to $B = \{-4,-3,4\}$: 
![[Pasted image 20230828102320.png|400]]
([Source](https://mathbooks.unl.edu/PreCalculus/Intro-to-Functions.html))

- In order for a rule of assignment to be a valid function according to this definition, two things must happen: 
	- Every point in $A$ (the [[Domain|domain]] of $f$) must actually have an output; that is, there can be no elements of $A$ that are unassigned or uncomputable. 
	- No point in $A$ can be sent to two different outputs. 
- However notice in the examples above, and below, that **it is within the definition for two different inputs to be sent to the same output** (a "collision"). We just cannot send *one* input to *two or more* outputs ("splitting"). 

## Examples and Non-Examples

Some examples are shown above; here are a few more. 

- The function $ceil: \mathbb{R} \rightarrow \mathbb{Z}$ takes a real number (floating point number) as input, and the output assigned is the integer you get when you round the input up. For example $ceil(9.22) = 10$. This is a function because every input does receive an output, and no input gets more than one. (However there are lots of collisions, where different inputs are sent to the same output; for example every number greater than 9 and less than or equal to 10 will be sent to 10.)
- 

## Resources 

(video)

Other resources: 
- 

## Practice 
