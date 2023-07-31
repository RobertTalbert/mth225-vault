---
aliases: [Division Algorithm]
--- 

#computer-arithmetic 

## Definition 

> [!tldr] Definition
> The **Division Algorithm** is a mathematical [[Theorem|theorem]] that states the following: 
> 
> For any two positive integers $a$ and $b$, there exist unique integers $q$ (the *quotient*) and $r$ (the *remainder*) such that $a = bq + r$ and $0 \leq r < b$. 

Notes: 
- The Division Algorithm as a [[Theorem]] does not state how the integers $q$ and $r$ are to be computed; it only asserts that they exist, and there is only one such pair that satisfies both of the requirements ($a = bq + r$ and $0 \leq r < b$). 
- As stated above, the Division Algorithm gives the quotient and remainder when dividing $a$ by $b$ (that is, $a \div b$). 
- The final requirement in the Division Algorithm statement, asserts that the remainder in the integer division process has to be strictly smaller than the divisor. This has important implications in computer algorithms involving division. 
- The actual process of finding the quotient and remainder is embodied in long division, which we learned in grade school. 
- In Python, the quotient when dividing $a$ by $b$ is computed using the operator `//` for [[integer division]]. The remainder when dividing $a$ by $b$ is computed using the operator `%` which is the [[The modulus operator|modulus operator]]. 

## Examples and Non-Examples

- If $a = 30$ and $b = 7$, then the quotient $q$ is $4$ and the remainder $r$ is $2$ because $30 = 7 \times 4 + 2$ and $0 \leq 2 < 7$. In Python, ``30 // 7 = 4`` and ``30 % 7 = 2`` . 
- If $a = 10$ and $b = 22$, then the quotient $q$ is $0$ and the remainder is $r = 22$ because $22 = 0 \times 100 + 22$ 

## Resources 

(video)

Other resources: 
- 

## Practice 
