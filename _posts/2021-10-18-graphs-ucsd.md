---
layout: post
title:  "Introduction to Graph Theory - UCSD"
date:   2021-10-18 12:36:27 +0800
categories: 
---

[https://www.coursera.org/learn/graphs](https://www.coursera.org/learn/graphs)

### Learning Objectives

- [x] __Define graphs__
	+   graphs represent a relationship between _pairs_ of objects. 
	+   $$G = (V, E)$$, where
		*   $$V$$, non-empty set of vertices
		*   $$E$$, set of edges
	+   simple; multigraph (loops, parallel edges)
	+   undirected; directed (tail → head)
	+   subgraph, proper subgraph
	+   open walk, closed walk, path, cycle, trail
- [ ] Practice graph drawing
- [x] Identify graph classes
	+   empty graph
	+   line graph 
	+   complete graph
	+   bipartite graph
	+   trees, rooted trees
	+   ... 
- [ ] Decide whether a graph has an Eulerian cycle
	+   a cycle that uses each edge exactly once
- [x] Apply the degree sum formula
- [x] Define planar graphs
	+   graph has a drawing where no 2 edges cross
- [ ] Prove that planar graphs can be colored in 6 colors
- [ ] Determine connected components of a graph
- [ ] Compute minimum spanning trees
- [ ] Describe matchings in bipartite graphs
- [ ] Develop an algorithm for the stable matching problem
- [ ] Analyze Ramsey numbers
- [ ] Review cliques, independent sets, and vertex covers
- [ ] Define augmenting paths in networks
- [ ] Compute maximum flows in graphs

***

#### Degree sum formula

$$ \sum_{v\in V} \deg v = 2|E| $$ 

Handshaking lemma, sum of degree of vertices = 2x edges 

#### Isomorphism

- must have the same number of vertices
- property of graph is preserved
- same up to a relabeling of vertices 
- computationally exhausting

#### Ways of representing graphs
1. adjacency matrix
2. adjacency list 
	- standard, linked lists
	- fast, hash tables
3. adjacency set
