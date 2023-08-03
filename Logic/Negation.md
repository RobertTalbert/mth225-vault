---
aliases: [negation]
--- 

#logic

## Definition 

> [!tldr] Definition
> The **negation** of a [[Propositions|proposition]] is another proposition with the opposite truth values. In mathematical notation, the negation of the proposition $P$ is $\neg P$ which is pronounced "not $P$". In this way the negation is a [[connective]] that modifies only one [[Propositions|proposition]]. 

Notes: 
- The English phrasing of a negation is often just putting the word "not" in the original [[Propositions|proposition]], but this sometimes leads to unintelligible statements. Often, some care is needed to phrase a negation in a way that makes sense to a listener or reader. 
- The [[Truth tables|truth table]] for the negation of a statement is built simply by reversing the truth values of the original. The basic truth table for $\neg P$ is: 

| $P$   | $\neg P$ |
| ----- | -------- |
| True  | False    |
| False | True         |

## Examples 

The negation of the statement "Bob had pizza for lunch" is "Bob did not have pizza for lunch". 

The negation of the statement "Bob had pizza for lunch and went for a walk" is more complicated. If we let $P$ represent the statement "Bob had pizza for lunch" and $W$ "Bob went for a walk" then the original statement is the [[conjunction]] $P \wedge W$. Its truth table is 

| $P$   | $W$   | $P \wedge W$ |
| ----- | ----- | ------------ |
| True  | True  | True         |
| True  | False | False        |
| False | True  | False        |
| False | False | False             |

The negation is *not* the statement, "Bob *did not* have pizza for lunch and *did not* go for a walk". This would be the statement $(\neg P) \wedge (\neg W)$ whose truth table is 

| $P$   | $W$   | $(\neg P$(\neg P) \wedge (\neg W)$ |
| ----- | ----- | ------------ |
| True  | True  | True         |
| True  | False | False        |
| False | True  | False        |
| False | False | False             |
## Resources 

(video)

Other resources: 
- 

## Practice 
