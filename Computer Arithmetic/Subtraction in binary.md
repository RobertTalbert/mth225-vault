---
aliases: [binary subtraction, base 2 subtraction]
--- 

#computer-arithmetic 

## Process 

> [!tldr] Process
> If $a$ and $b$ are base 2 (binary) integers and $a \geq b$, to find $a-b$:
> 1. Start in the ones ($2^0$) place and subtract the bits there: $0 - 0 = 0$, $1-1 = 0$, $1-0 = 1$; and if we encounter $0-1$ then **borrow** $1$ from the twos ($2^1$) place to make the $0$ into $10$, then subtract to get $10 - 1 = 1$. 
> 2. Subtract the bits in the twos ($2^1$) place. Again, $0 - 0 = 0$, $1-1 = 0$, $1-0 = 1$; and if we encounter $0-1$ then **borrow** $1$ from the fours ($2^2$) place to make the $0$ into $10$, then subtract to get $10 - 1 = 1$. 
> 3. Continue this process of subtracting, borrowing from the next higher place if needed, until we reach the left end of the bitstring. 

Notes: 
- It's also possible to "subtract" $b$ from $a$ by finding the binary form of $b$ using two's complement notation, then using binary addition to add this to $a$. However there are potential issues with the bit size; the procedure outlined above has no such restrictions. 

## Examples 

Subtract the [[Base 2 representation|base 2]] integers $1101$ and $1010$. That is, find $1101 - 1010$. Note that in base 10, this would be $13 - 10$, so the answer should be $3$ which is $11_2$. 
1. Subtract bits in the ones ($2^0$) place: $1-0 = 1$. 
2. Subtract bits in the twos ($2^1$) place: We have $0-1$ so we borrow $1$ from the fours ($2^2$) place to make the $0$ into a $10$, then subtract: $10 - 1 = 1$. 
3. Subtract bits in the fours ($2^2$) place: This would have been $1-1$ except we borrowed in the previous step, so the first $1$ is now a $0$. Therefore we have $0-0$ which is $0$. 
4. Subtract bits in the eights ($2^3$) place: $1-1 = 0$. 
Therefore $1101 - 1010 = 0011$ which is $11$. That's what we expected. 

## Resources 



Other resources: 
- 

## Practice 
