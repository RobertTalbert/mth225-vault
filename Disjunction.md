---
aliases: [disjunction]
--- 

#logic

## Definition 

> [!tldr] Definition
> A **disjunction** is a logical [[Connectives|connective]] joining two [[Propositions|propositions]], which results in a new proposition that is true only when one or both of the two propositions is true. It is the logical version of the english word "or". The notation for a conjunction is the symbol $\vee$, and we pronounced $A \vee B$ as "$A$ or $B$". 

Notes: 
- The [[Truth tables|truth table]] for the conjunction $A \vee B$ is: 

| $A$   | $B$   | $A \wedge B$ |
| ----- | ----- | ------------ |
| True  | True  | True         |
| True  | False | True        |
| False | True  | True        |
| False | False | False             |
Again, $A \vee B$ is true only when *either* $A$ *or* $B$, **or both**, is true. Because of this, we refer to disjunction sometimes as an *inclusive "or"*. 

- In Python, the conjunction is implemented by just the word `and`. 
- In other languages, the conjunction is frequently indicated by `&&`. 
## Resources 

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/585958504/#t=4m41s" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Screencast 2.2: Logical connectives"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

Other resources: 
- Tutorial: [Logical AND operator](https://learn.microsoft.com/en-us/cpp/cpp/logical-and-operator-amp-amp?view=msvc-170) (Microsoft)
