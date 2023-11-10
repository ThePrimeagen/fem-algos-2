---
title: "RB-Tree"
description: "Lets go over Red Black trees"
---

### Why are they called red black trees?
You are not the only one to ask this question

![Why Red/Black](./images/why-red-black.png)

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

![This Is Why](./images/why-red-black-1.png)

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

![This Is Why](./images/why-red-black-2.png)

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

### Now that we are disappointed, lets learn!
I will only be showing you the basics of Red Black Tree since they are
excessively complicated and would take too much time to go into detail

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

### The Rules of a RB tree
there are a few rules to a red black tree

1. all nodes are red or black
1. the root and nils are black
1. you cannot have a red parent and red child, or simply no 2 adjacent red nodes
1. all paths should have the same number of black nodes

<br/>
<br/>

### Lets draw up a basic red black tree

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

### Extra Notes and Runtime
Runtime: Search, Insert, and Delete all have a runtime of log(n)
* The longest path from root to nil is no more than twice as long as the shortest path
* Not as balanced as an avl, but requires less rotations on average than an avl tree

<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

