---
title: "MSTs"
description: "The minimum spanning algorithms"
---

### Spanning Tree
* What is a spanning tree?
  * requirements:
    * every node in the graph must be in the spanning tree
    * there cannot be any cycles

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

### Minimum Spanning Tree
* additional requirements
    * the summed weight of the graph's edges in the tree should be the smallest
* properties
    * how many edges are in any minimum spanning tree?
    * it may not produce the same tree depending on the node you start with

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

### The First Algorithm for MST
* Prim's algorithm
* start with simple edge based approach
* what is the runtime?

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

### What data structure can we use to make Prim's Faster?
... (scroll down to find out) ...

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

### Quick review of heap
* whiteboard
* heap condition
* how heaps are represented
* finding children and parent
* insert
* delete

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

### Lets reimagine how we are calculating Prim's
we will reduce the time complexity down to `|E|log|V|`

* lets think about what we are storing in our priority queue.
* we will also have to have a way to look up values in our priority queue in a O(1) way

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


### The Second Algorithm
* Kruskals

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

### Cycles?
Well there is a fun algorithm called Disjoin-set or Union-find.

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

### Path Compression
Lets rerun our Union Find algorithm but lets talk about and apply the path
compression algorithm

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

### Runtime of Kruskals
With Union-find Path Compression

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

### When to use
They say that prim's is better for dense and kruskals better for sparse.  I
honestly have never tested it and when someone says something is faster i just
don't believe them.

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


