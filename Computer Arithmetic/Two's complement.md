---
aliases: [two's complement]
--- 

#computer-arithmetic 

## Definition/Process 

> [!tldr] Process
> Two's complement is a method of representing a *negative* integer in binary. To put a negative integer in two's complement notation: 
> 1. Decide on the number of bits to use for the representation. (This often depends on the architecture of the computer system, e.g. an 8-bit system or a 64-bit system.)
> 2. Take the negative number in base 10 and write its *positive* version in base 2 (using the [[Base conversion algorithm|base conversion algorithm]]). 
> 3. Flip all the bits in this binary integer -- change all `0`s to `1`s and vice versa. 
> 4. Using binary addition, add `1` to this binary integer. 
> 
> The result is the two's complement representation of the original negative integer. 
>

Notes: 
- Other forms of representing negative integers in binary exist besides two's complement. [This page gives a summary](https://www.geeksforgeeks.org/representation-of-negative-binary-numbers/). 

## Examples 

Represent $-42$

## Resources 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/583067547?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Screencast 1.9: Two's complement representation"></iframe></div>


Other resources: 
- 

## Practice 
