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
> 2. Add the two bits in the "twos" place (that is, the $2^1$ digit) along with the `1` that was carried from the previous step, if applicable. The result will be one of the following: `0`, `1`, `10`, or `11`. If it's `0` or `1`, record this in the $2^1$ and move on to the ""


 


> Two add two base 2 integers together without first converting to base 10: 
> 1. Add the bits in the ones ($2^0$) place together: `0+0 = 0`, `1+0 = 1`, `0+1 = 1`, or `1+1 = 10`

(blurb)

## Examples and Non-Examples

## Resources 

(video)

Other resources: 
- 

## Practice 
