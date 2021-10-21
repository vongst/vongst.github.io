---
layout: post
title:  "Introduction to Graph Theory - UCSD"
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
	+   directed acyclic graphs
	+   trees, rooted trees
	+   ... 
- [x] Apply the degree sum formula
- [x] Define planar graphs
	+   graph has a drawing where no 2 edges cross

	
Graph colouring 
- [ ] Prove that planar graphs can be colored in 6 colors 
	+ [Five Color Theorem](https://proofwiki.org/wiki/Five_Color_Theorem)

Route problems
- [ ] Decide whether a graph has an Eulerian cycle
	+   a cycle that uses each edge exactly once
- [ ] Compute minimum spanning trees
- [ ] Define augmenting paths in networks

Network flow
- [ ] Describe matchings in bipartite graphs
- [ ] Develop an algorithm for the stable matching problem
- [ ] Compute maximum flows in graphs

Everything else
- [ ] Determine connected components of a graph
- [ ] Analyze Ramsey numbers
- [ ] Review cliques, independent sets, and vertex covers

***

#### Degree sum formula / Handshaking lemma

$$ \sum_{v\in V} \deg v = 2|E| $$ 

Sum of degree of all vertices = 2 * number of edges 

#### Isomorphism

$$G_{1} = (V_{1},E_{1})$$ is isomorphic to $$G_{2} = (V_{2},E_{2})$$ iff there exists a bijection $$f:V_{1}\rightarrow V_{2}$$ such that for every pair of vertices $$u,v \in V_{1}$$:

$$\{u,v\}\in E_{1} \iff \{f(u),f(v)\}\in E_{2}$$

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

---

### Route problems

### Graph colouring

### Network flow