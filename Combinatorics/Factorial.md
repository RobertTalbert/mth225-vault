---
aliases: [factorial, factorial function]
--- 

#combinatorics 

## Definition 

> [!tldr] Definition
> For any [[Integers|integer]] $n > 0$, the **factorial** of $n$, denoted $n!$, is the number 
> $$n! = 1 \cdot 2 \cdot 3 \cdot \cdots \cdot (n-1) \cdot n$$
> Furthermore we define $0! = 1$. 

**Notes**: 

- For our purposes, the factorial function is not defined if $n < 0$ or if $n$ is not an integer. 
- The number $n!$ represents the number of ways to take a group of $n$ distinct objects and rearrange them. 
- The previous point explains why we consider $0! = 1$ and not $0$: There is one and only one way to rearrange an empty group of zero objects, which is to do nothing. 
- The factorial can be defined [[Recursion|recursively]]: The base case is $0! = 1$ and for all $n > 0$, define $n!$ to be $n \cdot (n-1)!$. 
- Because of the previous point, many facts about factorials and formulas that use them are proven using [[Logic/Mathematical induction|mathematical induction]]. 
- Python provides a `factorial` function in the `math` library. Here is an example of use: 

```python
import math
math.factorial(15)
```

- You can also define it [[Recursion|recursively]]: 
```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```
## Examples 

- Here is a table with the first several values of the factorial: 

| $n$ | $n!$                             |
| --- | -------------------------------- |
| 0   | 1 (by definition)                |
| 1   | 1                                |
| 2   | $1 \cdot 2 = 2$                  |
| 3   | $1 \cdot 2 \cdot 3 = 6$          |
| 4   | $1 \cdot 2 \cdot 3 \cdot 4 = 24$ |
| 5   | $120$                            |
| 6   | $720$                                 |

- **How many ways are there to reorder the sequence of colors** 🔴🟡🟢 ? Answer: This is a group of 3 distinct objects and we are rearranging them, so there are $3! = 6$ rearrangements. Those are: 🔴🟡🟢 , 🔴🟢🟡, 🟢🔴🟡, 🟢🟡🔴, 🟡🟢🔴, and 🟡🔴🟢. 


## Resources 

- Tutorial: [Factorials](https://www.mathsisfun.com/numbers/factorial.html)
- Website: Properties of the factorial