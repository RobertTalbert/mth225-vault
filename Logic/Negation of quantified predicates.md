---
aliases: [negation of predicates]
--- 

#logic 

## Facts 

> [!tldr] Facts
> Suppose $P(x)$ is a predicate. Then: 
> - The negation of its existentially quantified form $\exists x P(x)$ is $\forall x (\neg P(x))$. 
> - The negation of its universally quantified form $\forall x P(x)$ is $\exists x (\neg P(x))$. 
> 
> That is: $\neg (\exists x P(x)) = \forall x (\neg P(x))$ and $\neg (\forall x P(x)) = \exists x (\neg P(x))$. 

Notes: 
- In English, this is saying: 
	- The negation of "There exists an $x$ such that $P(x)$ is true", is the statement "For all $x$, $P(x)$ is false."
	- The negation of "For all $x$, $P(x)$ is true", is the statement "There exists an $x$ such that $P(x)$ is false."
- Note that in each case we not only negate the predicate, but change the quantifier. 
- Negating a quantified [[multivariable predicate]] follows the same principles. 

## Examples and Non-Examples

Here are some quantified predicates with their negations, in regular English: 

| Quantified predicate                                                 | Symbolic form    | Negation of symbolic form | Negation in English                                                                                                                    |
| -------------------------------------------------------------------- | ---------------- | ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Every MTH 225 student has red hair.                                  | $\forall x P(x)$ | $\exists x (\neg P(x))$   | There is at least one MTH 225 student who does not have red hair.                                                                      |
| There is a student in your section of MTH 225 who is a millionaire. | $\exists x P(x)$ | $\forall x (\neg P(x))$   | Every student in your section of MTH 225 is not a millionaire. *Or:* None of the students in your section of MTH 225 are millionaires. |
| For each student in MTH 225, there is a tutor available. | $\forall x \exists y P(x,y)$ | $\exists x \forall y ()                                                                      |                  |                           |                                                                                                                                        |

## Resources 

(video)

Other resources: 
- 

## Practice 
