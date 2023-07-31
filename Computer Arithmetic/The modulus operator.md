---
aliases: [modulus, modulus operator, mod]
--- 

#computer-arithmetic 

## Definition 

> [!tldr] Definition
> The **modulus operator** `%` when applied to two integers $a$ and $b$, returns the unique value of the remainder $r$ given by the [[The division algorithm|Division Algorithm]] when dividing $a$ by $b$. 

Notes:
- The symbol `%` is used in Python and many other languages to implement the modulus operator. 
- According to the [[The division algorithm|Division Algorithm]], the result of `a % b` is always strictly less than $b$. 
- If $b = 0$ then `a % b` is undefined (and will throw an error in Python). 
- `a % b` can be found if $a$ is negative as well; see below for the procedure. 

## Examples and Non-Examples

- `100 % 8 = 4` because $8$ divides $100$, $12$ times with a remainder of $4$. 
- `100 % 5 = 0` because $5$ evenly divides $100$. 
- `225225 % 14 = 9`
 
To find `a % b` if $a$ is negative: Add $b$ to $a$ repeatedly until the result is non-negative (zero or higher). When this happens, the result is `a % b`. 

Example: To find `(-100) % 16`, start adding $16$ to $-100$ and stop when you hit zero or a positive result: 
- $-100 + 16 = -84$
- $-84 + 16 = -68$
- $-68 + 16 = -52$
- $-52 + 16 = -36$
- $-36 + 16 = -20$
- $-20 + 16 = -4$
- $-4 + 16 = 12$  STOP 
Therefore `(-100) % 16 = 12`. (There are other ways to do this as well)


## Resources 

(video)

Other resources: 
- 

## Practice 
