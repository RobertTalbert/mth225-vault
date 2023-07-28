---
aliases: [base 2 multiplication, binary multiplication]
--- 

#computer-arithmetic 

## Process 

> [!tldr] Process
>  If $a$ and $b$ are [[Base 2 representation|base 2]] ([[Base 2 representation|binary]]) [[integers]] and $a \geq b$, to find $a \times b$:
>  1. Multiply $a$ by the ones ($2^0$) digit in $b$. This will result either in a copy of $a$, or a row of zeroes. 
>  2. Underneath the result of the previous step, place a padding $0$ on the right. Then multiply $a$ by the twos ($2^1$) digit in $b$. This will result either in a copy of $a$, or a row of zeroes. 
>  3. Underneath the result of the previous step, place two padding $0$'s on the right. Then multiply $a$ by the fours ($2^2$) digit in $b$. This will result either in a copy of $a$, or a row of zeroes. 
>  4. Continue this process, adding an extra padding $0$ on the right each time, until you use the leftmost bit of $b$. 
>  5. Use [[Addition in binary|binary addition]] to add all the resulting rows together. 

## Examples 

Multiply $1101$ by $101$. In [[Base 10 representation|base 10]] this is $13$ times $5$, so the answer should be $91$ or $1011011$. 
1. Multiply $1101$ by the ones ($2^0$) digit in $11!
## Resources 

(video)

Other resources: 
- 

## Practice 
