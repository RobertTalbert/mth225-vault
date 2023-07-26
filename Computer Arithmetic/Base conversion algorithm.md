---
aliases: [base conversion algorithm]
--- 

#computer-arithmetic 

## Process 

> [!tldr] To convert a positive integer *from* base 10 *to* base $b$ where $b$ is any other number base: 
> Let $n$ be the integer in base 10 that you want to convert to base $b$. 
> 1. Divide $n$ by $b$. Let $q_1$ be the quotient (how many times $b$ goes into $n$) and let $r_1$ be the remainder. 
> 2. Now replace $n$ with $q_1$. Divide $q_1$ by $b$, and let $q_2$ be the new quotient and $r_2$ be the new remainder. 
> 3. Replace $q_1$ with $q_2$. Divide $q_2$ by $b$, and let $q_3$ be the new quotient and $r_3$ be the new remainder. 
> 4. Continue these steps (divide the previous quotient by $b$ and keeping the new quotient and new remainder) until the new quotient is $0$. In the final step where the new quotient is $0$, go ahead and keep the. new remainder (which will just be the number you divided into). 
> 5. The base $b$ representation of the original integer $n$, is **the sequence of remainders written in reverse order**. So, if there were $k$ steps in all, the base $b$ representation is $r_k r_{k-1} r_{k-2} \cdots r_3 r_2 r_1$. 

Notes: 
- The algorithm here always terminates because the quotients are nonnegative integers, and at each step must get strictly smaller, and therefore they will always converge to zero. 
- Here is Python code for this algorithm if the base is between 2 and 10. It terminates immediately if the base is larger than 10, because to convert to a larger base you would need alphabetical replacements for the numbers 10 and above, as in hexadecimal. You could modify this code, though, to work for larger bases if you introdu



## Examples and Non-Examples

## Resources 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/578187581?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Screencast 1.3: Base 10 conversion algorithm"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Other resources: 
- 

## Practice 
