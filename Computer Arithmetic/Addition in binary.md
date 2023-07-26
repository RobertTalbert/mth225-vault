---
aliases: [binary addition, base 2 addition, addition in binary]
--- 

#computer-arithmetic 

## Process 

> [!tldr] Process
> First note that if we are just adding two bits together, there are four possible ways to do this: `0+0`, `1+0`, `0+1`, and `1+1`. The sum `0+0` equals `0`. The sums `0+1` and `1+0` both equal `1`. The sum `1+1` equals `10` (that is, 2, written in base 2). 
> 
> Now if we want to add two positive integers in base 2 without converting to base 10 first: 
> 1. Add the two bits in the "ones" place (that is, the $2^0$ digit). If the two bits are anything other than `1` and `1`, record the resulting sum and move on to the "twos" place (that is, the $2^1$ digit). If the two bits are both `1`, the sum in the $2^0$ place is `0`, and carry a `1` over to the $2^1$ digit. 
> 2. Add the two bits in the "twos" place (that is, the $2^1$ digit) along with the `1` that was carried from the previous step, if applicable. The result will be one of the following: `0`, `1`, `10`, or `11`. If it's `0` or `1`, record this in the $2^1$ and move on to the "fours" place (that is, the $2^2$ digit). Otherwise record the lowest bit (either `0` or `1` ) and carry the `1` over to the the $2^2$ digit. 
> 3. Repeat this process of adding either 2 or 3 bits (depending on whether a `1` was carried or not) until you reach the leftmost end of the numbers you are adding. 

## Examples 

Add the base 2 integers $1011$ and $1010$. 

1. Add the ones digits: `1+0 = 1`. Record the `1` as the result. There's no carried `1` here so move on. 
2. Add the twos digits: `1+1 = 10`. Record `0` as the result and carry the `1`. 
3. Add the fours digits and the carried `1`: `1 + 0 + 0 = 1`. There's no carried `1` so move on. 
4. Add the eights digits: `1 + 1 = 10`. Record the `0` and carry the 1. 
5. There's no sixteens digits to add, so the carried `1` is the leftmost bit of the result. 

In other words, $1011 + 1010 = 10101$. Notice this checks out because $1011_2 = 11_{10}$ and $1010 = 10_{10}$, and in base 10 we know that $11 + 10 = 21$. And converting the result $10101_2$ back to base 10 gives $21$ as it should. 

## Resources 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/578516501?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Screencast 1.4: Addition in binary"></iframe></div>

Other resources: 
- [Khan Academy video on binary addition](https://www.youtube.com/watch?v=RgklPQ8rbkg&pp=ygUPYmluYXJ5IGFkZGl0aW9u)
- [Video on addition (and subtraction) of binary integers](https://www.youtube.com/watch?v=C5EkxfNEMjE)
- 

## Practice 
