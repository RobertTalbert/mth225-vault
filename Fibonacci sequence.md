---
aliases: [Fibonacci number, Fibonacci numbers]
--- 

#recursion-induction 

## Definition 

> [!tldr] Definition
> The **Fibonacci sequence** is the [[Sequence|sequence]] defined by the following second-order [[Recurrence relation|recurrence relation]]: 
> - The first two terms are $f_1 = 1$ and $f_2 = 1$. 
> - For all $n > 2$, $f_n = f_{n-1} + f_{n-2}$. 
>  
> This produces the sequence $1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, \dots$.   

Notes: 
- [Here is a list of the first 1000 Fibonacci numbers](https://listry.com/list-of-the-first-1000-fibonacci-numbers/). 
- Below is a [[Recursion|recursive]] Python function that will produce the $n$th Fibonacci number. Beware, it gets very slow quite quickly. 

```python
def fib(n): 
	if n == 1 or n == 2:
		return 1
	else:
		return fib(n-1) + fib
```

## Examples and Non-Examples

## Resources 

(video)

Other resources: 
- 

## Practice 
