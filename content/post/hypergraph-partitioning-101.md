---
title: "Hypergraph Partitioning 101"
date: 2017-09-20T12:25:35-04:00
lastmod: 2017-09-20T12:25:35-04:00
draft: true 
keywords: []
description: ""
tags: []
categories: []
author: "Ruslan Shaydulin"

# you can close something for this content if you open it in config.toml.
comment: false
toc: false
# you can define another contentCopyright. e.g. contentCopyright: "This is an another copyright."
contentCopyright: false
reward: false
mathjax: true
---
## Topic no one knows about 

More often than not, I get a blank stare when I tell people what my research is about. Hypergraph partitioning may seem to be an obscure topic no one knows (or cares much) about. But by the end of this post, you'll know that is not the case.

In this post, I'll try to answer three basic questions:

1. What is a hypergraph and what is partitioning?

2. Why would you want to partition a hypergraph?

3. How would you partition it?

Without much further ado, let's get started.
 
<!--more-->

## So what is a hypergraph?

Hypergraph is a simple generalization of a graph: whereas in a graph each edge connects just two nodes, in hypergraph an edge can connect an arbitrary number of nodes[^1]. 

Whereas \\(G\in E\\), in blank \(\forall E\)

$$G = (V,E) \forall e\in E$$

[^1]: In other words, if graph is a pair of sets \\(G=(V,E)\\), where \\(V\\) is the set of vertices, \\(E\\) is the set of edges and the cardinality of each element in \\(E\\) is 2 (\\(|e| = 2\,\forall e\in E\\)), a hypergraph is the same pair \\(H = (V,E)\\), except the cardinality of elements in \\(E\\) is not limited. 
