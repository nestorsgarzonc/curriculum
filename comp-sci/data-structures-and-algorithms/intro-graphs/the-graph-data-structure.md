---
author: mihaiberq

levels:

  - beginner

type: normal

category: must-know

aspects:

  - introduction

  - workout

links:

  - '[Graph theory](https://en.wikipedia.org/wiki/Graph_theory){website}'

parent: the-queue-data-structure

---

# The Graph Data Structure

---
## Content

**Graphs** are a way of representing relationships between pairs of objects. They consist of objects (called *nodes* or *vertices*) and the pairwise connections between them (called *edges*).

Graphs come in two flavors: **directed graphs** (*digraph*) and **undirected graphs**. In a directed graph the edges have a direction, like a one-way street. Conversely, in an undirected graph, the edges have no notion of direction.

This is how an undirected graph is represented:

![undirgraph](https://img.enkipro.com/bf52325a6f6a0464d8e2c09e01480049.png)

In the above example, `A` is a node, and the line connecting node `A` and node `C` is an **edge**.

And this is a directed graph:

![dirgraph](https://img.enkipro.com/68f62123d7690d4b01edb2c7c7a1c9d1.png)

For example, *linked lists* are special a kind of directed graphs.

Graphs can be used to represent friendships on social networks. *Facebook*, for instance, is organized as an *undirected graph* (you appear on each other's friend list), while *Twitter*, is organized as a *directed graph* (you can follow someone without them having to follow you back).

There can be more *directed edges* with the same origin and destination nodes, and more *undirected edges* to have the same end nodes. These are called **parallel edges** or **multiple edges**.

A **self-loop** is an edge for which the 2 nodes coincide.

A graph containing both parallel edges and a self loop is represented below:

![notsimplegraph](https://img.enkipro.com/d82b7624ea78d9218a0410acf177f982.png)

We call **simple graph** one that does *not contain self-loops or multiple edges*. The first two graphs are simple.

---
## Practice

A graph that represents flight routes between cities should be

 ???.


* directed
* undirected

---
## Revision

What's the name for an edge in a graph that connects a node with itself?

???

* self-loop
* simple edge
* circular edge
* self-connection


