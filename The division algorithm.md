---
aliases: [Division Algorithm]
--- 

#computer-arithmetic 

## Definition 

> [!tldr] Definition
> The **Division Algorithm** is a mathematical [[theorem]] that states the following: 
> 
> For any two positive integers $a$ and $b$, there exist unique integers $q$ (the *quotient*) and $r$ (the *remainder*) such that $a = bq + r$ and $0 \leq r < b$. 

Notes: 
- The Division Algorithm as a [[theorem]] does not state how the integers $q$ and $r$ are to be computed; it only asserts that they exist, and there is only one such pair that satisfies both of the requirements ($a = bq + r$ and $0 \leq r < b$). 
- As stated above, the Division Algorithm gives the quotient and remainder when dividing $a$ by $b$ (that is, $a \div b$). 
- The final requirement in the Division Algorithm statement, asserts that the remainder in the integer division process has to be strictly smaller than the divisor. This has important implications in computer algorithms involving division. 
- In Python, the quotient when dividing $a$ by $b$ is computed using the operator `//` for [[integer division]]. The remainder when dividing $a$ by $b$ is computed using the operator `%` which is the [[The modulus operator|modulus operator]]. 

## Examples and Non-Examples

- If $a = 30$ and $b = 7$, then the quotient $q$ is $4$ and the remainder $r$ is $2$. 

## Resources 

(video)

Other resources: 
- 

## Practice 