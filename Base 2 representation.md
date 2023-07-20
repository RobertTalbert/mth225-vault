---
aliases: [binary, base 2, bit]
--- 

#computer-arithmetic 

## Definition 

> [!tldr] Definition
> An [[Integers|integer]] is written in **base 2** or **binary** format if it consists of a string of the numbers $0$ and $1$, called **[[binary digits]]** or "**bits**",  that represent groupings of power of 2. 

Notes: 
- A group of 8 bits is known as a **byte**. 
- Every positive integer can in fact be written as a sum of powers of 2 and in only one way. This fact can be proven using [[mathematical induction]].
## Examples 

The number $267$ can be written as a sum of powers of $2$ as follows: 
$$267 = 256 + 8 + 2 + 1 = 2^8 + 2^3 + 2^1 + 2^0$$
Using $0$ to pad this sum with groups that are not used and $1$ multiplied to groups that are use, this becomes: 
$$267 = 256 + 8 + 2 + 1 = 1 \cdot 2^8 + 0 \cdot 2^7 + 0 \cdot 2^6 + 0 \cdot 2^5 + 0 \cdot 2^4 + 1 \cdot 2^3 + + 0 \cdot 2^2 + 1 \cdot 2^1 + 1 \cdot 2^0$$
The resulting string of $0$'s and $1$'s, read left-to-right, is the binary representation of 267: 
$$267 \ \text{base 10} = 100001011 \ \text{base 2}$$
A subscript is often used to indicate which base we mean: $267_{10} = 100001011_{2}$. 

Likewise, the number 24 is $24 = 16 + 8 = 1 \cdot 2^4 + 1 \cdot 2^3 + 0 \cdot 2^2 + 0 \cdot 2^1 + 0 \cdot 2^0$. Therefore $24_{10} = 11000_2$. 

## Resources 


## Practice 
