---
aliases: [characteristic root method, characteristic root technique, characteristic equation, characteristic root]
--- 

#recursion-induction 

## Definition 

> [!tldr] Definition
> The **characteristic root method** is a technique for deriving a [[Solution to a recurrence relation|solution]] to a [[Linear recurrence relation|linear]] [[Homogeneous recurrence relation|homogeneous]] recurrence relation. The general method is as follows: 
> 1. Put the recurrence relation in "standard form" with the new term on the left side of the equals sign and all other objects on the right side. 
> 2. Replace $a_{n}$ with $x^n$, $a_{n-1}$ with $x^{n-1}$, and so on until all sequence terms are replaced with powers of $x$. 
> 3. Divide both sides by the smallest power of $x$ to arrive at a polynomial equation. (This equation is known as the *characteristic equation* for the recurrence relation.) 
> 4. Solve the polynomial equation using basic algebra techniques. The resulting value(s) of $x$ are called the *characteristic roots* of the recurrence relation. 
> 5. If $x_1, x_2, \dots, x_k$ are the characteristic roots, the general form of the [[Solution to a recurrence relation|solution]] to the recurrence relation is $a(n) = \alpha_1 x_1^n + \alpha_2 x_2^n + \cdots + \alpha_k x_k^n$ where $\alpha_1, \alpha_2, \dots, \alpha_k$ are unknown constants. 
> 6. Use the initial conditions of the recurrence relation to find the values of $\alpha_1, \alpha_2, \dots, \alpha_k$. This involves solving a [system of linear equations](https://www.mathsisfun.com/algebra/systems-linear-equations.html). 



## Example

Consider the second-[[Recurrence relation|order]] [[Linear recurrence relation|linear]] [[Homogeneous recurrence relation|homogeneous]] recurrence relation: $a_0 = 1, a_1 = 2$; and for $n > 1$, $a_n = 5a_{n-1} - 6a_{n-2}$. This recurrence relation is already in "standard form" with the highest term isolated on the left. Replace $a_n$ with $x^n$ and similarly for the other terms to get: 
$$x^n = 5x^{n-1} - 6x^{n-2}$$ Divide off by the smallest power of $x$, which in this case is $x^{n-2}$ to get: 
$$x^2 = 5x - 6$$
This is the same as $x^2 - 5x + 6 = 0$. Factor this to get: 
$$(x-3)(x-2) = 0$$
Therefore the characteristic roots are $x = 3$ and $x = 2$. Set up the solution to the recurrence relation: 
$$a(n) = \alpha_1 3^n + \alpha_2 2^n$$
Now we will use the initial conditions to find the two constants. Those conditions were $a_0 = 1$ and $a_1 = 2$. Plugging in $n = 0$ gives $a(0)$ on the left which equals $1$, and it gives $\alpha_1 3^0 + \alpha_2 2^0$ on the right which equals $\alpha_1 + \alpha_2$. Therefore $\alpha_1 + \alpha_2 = 1$. Similarly, plugging in $1$ for $n$ gives the equation  $3\alpha_1 + 2\alpha_2 = 2$. 
## Resources 

(video)

Other resources: 
- 

## Practice 
