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
- Some treatments of the Fibonacci sequence are zero-indexed, so that $f_0 = 1, f_1 = 1, f_2 = 2, f_3 = 3, f_4 = 5, f_6 = 8$ and so on. Other treatments are zero-indexed but the zero-th term is defined to be zero, so $f_0 = 0, f_1 = 1, f_2 = 1, f_3 = 2, f_4 = 3, f_6 = 5$, and so on. When looking up information about this sequence, take care to understand how the author is defining the terms. 
- [Here is a list of the first 1000 Fibonacci numbers](https://listry.com/list-of-the-first-1000-fibonacci-numbers/). 
- Below is a [[Recursion|recursive]] Python function that will produce the $n$th Fibonacci number. Beware, it gets very slow quite quickly. 

```python
def fib(n): 
	if n == 1 or n == 2:
		return 1
	else:
		return fib(n-1) + fib(n-2)
```

- If the above function is defined, the list comprehension `[fib(n) for n in range(1,21)]` will produce a Python list of the first 20 Fibonacci numbers. Change the upper end of the range to suit your needs, but take heed of the warning about slowdowns. 

## Resources 

- [Tutorial on Fibonacci numbers](https://www.mathsisfun.com/numbers/fibonacci-sequence.html)
- [Video: What is the Fibonacci sequence and why is it important?](https://www.youtube.com/watch?v=v6PTrc0z4w4)