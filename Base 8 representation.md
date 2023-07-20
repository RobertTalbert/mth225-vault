---
aliases: [octal, octal representation, base 8]
--- 

#computer-arithmetic 

## Definition 

> [!tldr] Definition
> An [[Integers|integer]] is written in **base 8** or **octal** format if it consists of a string of the numbers $0$ through $7$ that represent groupings of powers of 8. 

Notes: 
- The first few powers of $8$ are: 

| Power of $8$ | Value |
| :------------: | :-----: |
| $8^0$        | $1$   |
| $8^1$        | $8$   |
| $8^2$        | $64$  |
| $8^3$        | $512$ |
| $8^4$        |  $4096$     |

These are all powers of $2$ as well, since $8 = 2^3$. 
## Examples 

The number $267$ can be written as a sum of powers of $2$ as follows: 
$$267 = 4 \times 64 + 1 \times 8 + 3 \times 1 = 4 \times 8^2 + 3 \times 8^1 + 4 \times 8^0$$
Therefore $267$ in base 10, is $413$ in base 8. 
A subscript is often used to indicate which base we mean: $267_{10} = 413_{8}$. 

Likewise, the number 24 is $24 = 3 \times 8 = 3 \cdot 8^1 + 0 \times 8^0$. Therefore $24_{10} = 30_8$. 
## Resources 
This video starting at the 3:00 mark has more on binary representation: 
<iframe src="https://player.vimeo.com/video/575905500?h=463d7f680d" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<p><a href="https://vimeo.com/575905500">Screencast 1.1: Base 10 and Base 2 representation of integers</a> from <a href="https://vimeo.com/user132700952">Robert Talbert</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

Other resources: 
- [RapidTables web page for converting from base 10 to base 2](https://www.rapidtables.com/convert/number/decimal-to-binary.html)
- [Calculator.net page, includes conversion from base 10 to base 2 and vice versa](https://www.calculator.net/binary-calculator.html)
- [Converting from base 10 to base 2 in Excel](https://smallbusiness.chron.com/convert-decimals-binary-numbers-using-excel-39699.html), using the `DEC2BIN` function
## Practice 

1. Generate a random positive integer. Start small (1-4) digits at first. [Use this website](https://www.random.org/integers/) to generate random integers. 
2. Write the integer as a sum of powers of 2, then write its binary form. 
3. Check your work using the websites above. 

Some samples are below. 

| Base 10 | Base 2   |
| ------- | -------- |
| 248     | 11111000 |
| 130     | 10000010 |
| 135     | 10000111 |
| 255     | 11111111 |
| 214     | 11010110 |
