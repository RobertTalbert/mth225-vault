
---
aliases: [conditional statement, if-then statement, hypothesis, conclusion]
--- 

#logic 
## Definition 

> [!tldr] Definition
> A **conditional statement** is a [[Propositions|proposition]] that has the form "If $A$, then $B$" where $A$ and $B$ are [[Atomic and molecular propositions|atomic statements]]. The proposition $A$ in the "if" part is called the **hypothesis** of the conditional statement, and the proposition $B$ in the "then" part is called the **conclusion**. 
> 
> The conditional statement "If $A$ then $B$" is written in mathematical notation as $A \rightarrow B$. 

Notes:
- Conditional statements need not literally be phrased as "if-then" statements; any phrasing that indicates a conclusion follows from a hypothesis is equivalent. For example, here are five different ways to phrase the conditional statement "If it's snowing, then it's cold": 
	- *Snowing implies that it's cold*.
	- *It's cold whenever it's snowing.*
	- *Snowing is a sufficient condition for it to be cold.*
	- *Being cold is a consequence of it snowing.*
	- *Being cold follows from it snowing.*
	[See this article for more](https://math.stackexchange.com/questions/42042/different-ways-to-express-if-then). 

The [[Truth tables|truth table]] for the conditional statement $P \rightarrow Q$ is: 

| $P$ | $Q$ | $P \rightarrow Q$ | 
| -- | -- | ---- |
| T | T | T | 
| T | F | F | 
| F | T | T | 
| F | F | T | 

> [!important] When are conditional statements false? 
> Conditional statements are false only in one case: When the hypothesis is true but the conclusion is false. (That is, the consequence does not follow from the condition.)

## Examples 

Here are examples of conditional statements with the hypothesis and conclusions indicated: 

| Statement                                                                  | Hypothesis           | Conclusion    |
| -------------------------------------------------------------------------- | -------------------- | ------------- |
| If Bob has pizza, he'll get sick.                                          | Bob has pizza        | Bob gets sick |
| If $x > 3$ then $x^2 > 9$.                                                 | $x > 3$              | $x^2 > 9$     |
| A running time longer than 3 minutes follows from the input being too big. | The input is too big | The running time is longer than 3 minutes              |

Note the last example shows that the hypothesis of the conditional statement doesn't have to appear at the first of the sentence; it is merely the condition that triggers the response. 
## Resources 

## Practice 
