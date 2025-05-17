---
layout: default
title: Data Structures and Algorithms
date: 2024-03-20
categories: [Programming, Computer Science, Algorithms]
---

In my journey to know common data structures and algorithms we use and are often asked in interview questions. I started capturing my thoughts about them from a first principles perspective. This blog in its eutopian state (which it will never reach) should be enough to get you ready for the job and its interviews. This blog will have syntaxes written in python language.

## Common Data structures used:

Do we think human brains also have data structures? If yes, then what it is? Would it make us write better computers if we know how data is stored in brain? What makes us recall something faster and what almost never comes back in our memory? I think more the connections of a certain "object or idea", we tend to recall it better. Okay, enough of the analogy, let's look at common data structures we use in computers. 

1. **Array/Lists** -> A list/array of items. If its homogenous then we can call it an array, else call it list. Our brains mostly keep list of items, don't think we maintain arrays. Arrays are smart in memory management and allocate themselves a contiguous portion in memory. Still a research area to know how humans store them or do we have data structures like lists in human brain.

``` {python}
    arr: List[int] = []
    arr.append(1)
    arr.append(1)
    arr.remove(1)
    len(arr)
    arr[:2]
    arr.index(2)
    arr.reverse()
    arr.sort()
```
2. **Maps** -> When do we need maps? -> whenever we need to link things together? It stores key value pair. you know the key, you want to know the value. Imagine you know the product item, you want to know its price, you would need a map. Basically, as the name goes "map things". Python likes to call it dictionary, originating from mapping meaning of the words. 

```{python}
map = {}
map[1] = "python"
map[2] = "java"
map.keys()
map.items()
map.values()
map.pop(1) ## removes python from the map.

```

3. **Queues** -> They are special lists. which follows FIFO principle. You can add new elements using enqueue() and remove using dequeue() 

```

---

## Discussion

Have thoughts or questions about this post? Join the discussion on GitHub!

[![GitHub Discussions](https://img.shields.io/github/discussions/jinhub/jinhub.github.io?label=Join%20Discussion&style=for-the-badge)](https://github.com/jinhub/jinhub.github.io/discussions)
