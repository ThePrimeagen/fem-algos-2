---
title: "M-way Search Tree"
description: "The wildest of the trees"
---

### Binary Search Trees
But bigger, faster, stronger
* The daft punk of data structures

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

### Lets start by imagining an M-way Search Tree

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

### What is the problem with M-way search trees?
Well... its the same as a binary search tree.

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

### The B-tree
They are m-way search trees with a properties that make them self balancing

<br/>

**terminology**
* Leaf vs Internal vs Root
* What are keys?

<br/>

**properties**
* they follow the principals of m-way trees
* all leaves are at the same  depth

<br/>

**node properties**
* keys are stored in ascending order
* there is a lower and upper bound worth of keys that can be stored in any node
  - this is called "the minimum degree of a tree" (called t, t >= 2)

<br/>

**lower bound**
* every node but root has `t - 1` keys
* every internal node but the root has at least `t` children

**upper bound**
* every node can have at most `2t - 1` keys
* which means every node can have at most `2t` children

<br/>
<br/>

**common b-tree**
t = 2 creates a 2-3-4 tree

<br/>

given the rules:
* at least `t - 1` keys, 1
* at least `t` children for internal nodes is, 2
* at most `2t - 1` keys, 3
* at most `2t` children, 4

<br/>
this means that any internal node must have 2, 3, or 4 children

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

### Insertions
* ...

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

### Deletions
This is where all the rules come into play.  This is going to be the most
complicated data structure we have done and will do

<br/>

**NOTE: there is a more efficient route by ensuring that all nodes down the recursion path have `t` keys (requires merging)**
but we wont be doing that

<br/>

**leaf deletes**
**case a**: simple delete from leaf where the leaf has `t+` keys
* just delete it
**case b**: delete from leaf where leaf has `t - 1` keys, but right/left sibling has `t+` keys
* borrow key through the parent
**case c**: delete from leaf where siblings don't have borrowable nodes
**case d**: delete from leaf where siblings don't have borrowable nodes and neither does parent

<br/>

**internal deletes**

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

