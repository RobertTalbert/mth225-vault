---
aliases: [permutation, permutations]
--- 

#combinatorics 

## Definition 

> [!tldr] Definition
> A **permutation** of a set of objects is a possible rearrangement of those objects. 

**Notes:**

- The number of permutations of a set of $n$ **distinct** objects is $n!$ ($n$ factorial). 
- The number of permutations of a set of $n$ objects *not all of which are distinct* is less than $n!$ because simply computing a factorial overcounts the repeated objects. To correct the overcount, we must divide off by the number of ways to rearrange each cluster of distinct objects. For example the word "success" is 7 letters long but contains two copies of "c" and three copies of "s". The number $7!$ counts the number of ways to rearrange the letters if we assume the repeated letters are different. But since they are not, we overcount those by a factor equal to the number of ways to arrange each repeated group: $2! = 2$ for the "c", and $3! = 6$ for the "s". The correct number of permutations is therefore $7!/(3! \cdot 2!) = 420$. 
- The Python library itertools contains functions for enumerating permutations of sets. More here: https://docs.python.org/3/library/itertools.html For example the following code will print a list containing all 420 distinct permutations of the word "success": 

```python
import itertools
p = itertools.permutations("success")

# The permutations function includes duplicate elements. 
# Converting the list to a set and then back to a list removes 
# all the duplicates. 
list(set(([i for i in p])))
```

## Examples 

- There are 6 permutations of the letters X, Y, and Z: XYZ, XZY, YXZ, YZX, ZXY, ZYX. 
- There are 24 permutations of the letters X, Y, Z, and T: 
```
('x', 'y', 'z', 't'), ('x', 'y', 't', 'z'), ('x', 'z', 'y', 't'), ('x', 'z', 't', 'y'), ('x', 't', 'y', 'z'), ('x', 't', 'z', 'y'), ('y', 'x', 'z', 't'), ('y', 'x', 't', 'z'), ('y', 'z', 'x', 't'), ('y', 'z', 't', 'x'), ('y', 't', 'x', 'z'), ('y', 't', 'z', 'x'), ('z', 'x', 'y', 't'), ('z', 'x', 't', 'y'), ('z', 'y', 'x', 't'), ('z', 'y', 't', 'x'), ('z', 't', 'x', 'y'), ('z', 't', 'y', 'x'), ('t', 'x', 'y', 'z'), ('t', 'x', 'z', 'y'), ('t', 'y', 'x', 'z'), ('t', 'y', 'z', 'x'), ('t', 'z', 'x', 'y'), ('t', 'z', 'y', 'x')
```

## Resources 

<iframe src="https://player.vimeo.com/video/626473882?h=92e0a801af" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>
<p><a href="https://vimeo.com/626473882">Screencast 4.8: Rearrangements and k-permutations</a> from <a href="https://vimeo.com/user132700952">Robert Talbert</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

Other resources: 
- Tutorial: [Combinations and permutations](https://www.mathsisfun.com/combinatorics/combinations-permutations.html)