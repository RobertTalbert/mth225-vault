---
aliases: [logically equivalent]
--- 

#logic 
## Definition 

> [!tldr] Definition
> Two [[propositions]] are said to be **logically equivalent** if they have the same truth value in each variation of truth values in their [[Atomic and molecular propositions|atomic statements]]. If $P$ and $Q$ are logically equivalent, we write $P \equiv Q$. 

Notes: 
- Two logically equivalent propositions will have the same [[Truth tables|truth tables]] for each possible combination of truth values. In fact, one way to determine if two propositions are logically equivalent, is to construct and then compare their truth tables. 
- Variations on the notation $\equiv$ exist. For example, sometimes it's written $P \cong Q$, or $P \sim Q$. 

## Examples and Non-Examples

The propositions $P \rightarrow Q$ and $(\neg P) \vee Q$ are logically equivalent, as shown by their truth tables: 

| $P$ | $Q$ | $P \rightarrow Q$ | 
| -- | -- | ---- |
| T | T | T | 
| T | F | F | 
| F | T | T | 
| F | F | T | 

| $P$ | $Q$ | $\neg P$ | $(\neg P) \vee Q$ | 
| -- | -- | ---- |  ---- |
| T | T | F | T
| T | F | F | F
| F | T | T | T
| F | F | T | T


Likewise, one of [[DeMorgan's Laws]] states that $\neg(P \vee Q) \equiv (\neg P) \wedge (\neg Q)$. Here are the truth tables side by side with the final statements indicated with a vertical arrow:

| $P$   | $Q$   | $P \vee Q$ | $\stackrel{\Downarrow}{\neg(P \vee Q)}$ | $\neg P$ | $\neg Q$ | $\stackrel{\Downarrow}{(\neg P) \wedge (\neg Q)}$ |
| ----- | ----- | ---------- | --------------------------------------- | -------- | -------- | ------------------------------------------------- |
| True  | True  | True       | False                                   | False    | False    | False                                             |
| True  | False | True       | False                                   | False    | True     | False                                             |
| False | True  | True       | False                                   | True     | False    | False                                             |
| False | False | False      | True                                    | True     | True     | True                                                  |


## Resources 

(video)

Other resources: 
- Book section: [Logically equivalent statements](<https://math.libretexts.org/Bookshelves/Mathematical_Logic_and_Proof/Book%3A_Mathematical_Reasoning__Writing_and_Proof_(Sundstrom)/02%3A_Logical_Reasoning/2.02%3A_Logically_Equivalent_Statements>)
- 

## Practice 
