---
aliases: [base 2 division, binary division]
--- 

#computer-arithmetic 

## Process 

> [!tldr] Process
>   If $a$ and $b$ are [[Base 2 representation|base 2]] ([[Base 2 representation|binary]]) [[integers]] and $a \geq b$, to find $a \div b$:
>   First define division of single bits: $0 \div 1 = 0$, $1 \div 1 = 1$, and division by $0$ is meaningless.  
>   If $a$ and $b$ are larger than single bits, first remove any leading $0$ bits that are on the left. Then, use a modified form of long division: 
> 1. Compare the divisor (the number that is doing the division) with the first digit of the dividend (the number that is being divided). If you can divide evenly by the divisor, the first digit of the quotient (the result) is $1$. Otherwise it is $0$. 
> 2. Append the next digit to the dividend and repeat this process, appending digits until you get $1$. 
> 3. Once you have a $1$ in the quotient, multiply the divisor by $1$ (which is just making a copy of the divisor) and write it underneath the dividend. 
> 4. Then use [[Subtraction in binary|binary subtraction]] to subtract the divisor from the part of the dividend that it sits under. 
> 5. Bring down the next digit of the dividend and repeat this process. 
> 6. Continue the process of finding digits of the quotient and performing [[Subtraction in binary|binary subtraction]] until no more division can be done. 
> 7. The remainder of this division process will be either $0$ or $1$; $0$ if the divisor evenly divides the last step in the subtraction process or $1$ if it doesn't. 



$$\longdiv{10}{2}$$ 
## Examples 

Multiply $1101$ by $101$. In [[Base 10 representation|base 10]] this is $13$ times $5$, so the answer should be $65$ or $1000001$. 
1. Multiply $1101$ by the ones ($2^0$) digit in $101$ which is $1$. This produces a copy of $1101$. 
2. Pad on the right with a single $0$ and multiply $1101$ by the twos ($2^1$) digit of $101$. This is a $0$, so the result is $00000$. 
3. Pad on the right with two zeroes and multiply $1101$ by the fours ($2^2$) digit of $101$. This is a $1$, so the result is $110100$ (a copy of $1101$ along with the two padding zeroes). 
4. There are no more [[Binary digits and bitstrings|bits]] in $b$ to multiply by, so now add all the results above in [[Base 2 representation|binary]]: $1101 + 00000 + 110100$. The result is $1000001$ as expected. 
## Resources 

<iframe src="https://player.vimeo.com/video/580457312?h=b1d9b0e518" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<p><a href="https://vimeo.com/580457312">Screencast 1.6: Multiplication in binary</a> from <a href="https://vimeo.com/user132700952">Robert Talbert</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

Other resources: 
- [Binary arithmetic calculator](https://www.calculator.net/binary-calculator.html)
- Video: [Multiplying in binary](https://www.khanacademy.org/math/algebra-home/alg-intro-to-algebra/algebra-alternate-number-bases/v/binary-multiplication) (Khan Academy)
- [Tutorial on binary multiplication](https://www.cuemath.com/numbers/binary-multiplication/)

## Practice 

To practice this concept: Just make up pairs of random positive integers and convert to binary (or make up pairs of random [[Binary digits and bitstrings|bitstrings]]). Then multiply them. Then check your work by either using the [binary arithmetic calculator](https://www.calculator.net/binary-calculator.html) or by converting the answer to [[Base 10 representation|base 10]] and seeing if it matches what you should get if you multiplied the original integers together in [[Base 10 representation|base 10]]. 