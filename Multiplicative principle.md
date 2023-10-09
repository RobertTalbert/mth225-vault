---
aliases: [multiplicative principle, multiplication principle, Multiplication Principle]
--- 

#combinatorics

## Definition 

> [!tldr] Definition
> The **multiplicative principle** of counting states that if an event $A$ can occur in $m$ ways, and another event $B$ can occur in $n$ different ways, then the number of ways for $A$ and $B$ to happen simultaneously is $m \cdot n$. 

Notes: 
* The multiplicative principle is used when counting the number of outcomes of a process where the steps in the process are independent of each other and we know the number of outcomes of each step. 
* The multiplicative principle can be extended to more than two events. 

## Examples and Non-Examples

- (*The "license plate" problem*) The license plate numbers in a certain state consist of three letters (A through Z) and three digits (0 through 9). How many possible license plate numbers are there? Think of choosing a license plate number as a six-step process: Choose the first letter, then the second, then the third; then choose the first digit, then the second, then the third. There are $26$ ways to choose each letter (and the choice of a letter in one step doesn't influence the choice in the next step); and there are $10$ ways to choose each digit. So the total number of license plate numbers is $26 \cdot 26 \cdot 26 \cdot 10 \cdot 10 \cdot 10 = 17, 576, 000$. 
- What if no duplicates of either letters or digits were allowed? It's still a six-step process. There are 26 choices for the first letter, now 25 for the second, and 24 for the third; likewise there are 10 choices for the first digit, now 9 for the second, and 8 for the third. The total number of license plate numbers is therefore $26 \


## Resources 

<iframe title="vimeo-player" src="https://player.vimeo.com/video/618309204?h=17b1d061c9" width="640" height="360" frameborder="0"    allowfullscreen></iframe>

Other resources: 
- Wikipedia article: [Addition principle](https://en.wikipedia.org/wiki/Addition_principle)
