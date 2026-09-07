---
title: "Can We Break Fine-Grained and NP-Hardness Barriers if We’ve Seen the Graph Before? The Isomorphic-Priors Model"

authors:
  - Dani Dorfman
  - Simon Döring
  - Martin Herold
  - Danupon Nanongkai
  - Daniel Neuen
  - Joachim Spoerhase
  - Zihang Wu

date: '2026-11-08T00:00:00Z'
doi: ''

publishDate: '2026-09-07T00:00:00Z'

publication_types: ['paper-conference']

publication: In *FOCS*
publication_short: In *FOCS* 2026

abstract: If we run a heavy-duty computation on prior data, can we avoid repeated computation for similar future inputs? Inspired by this question, we introduce a new computational model for graph problems called algorithms with isomorphic priors. Solving a graph problem Pi in this model involves two phases:
  (i) the preprocessing phase quickly analyzes prior graphs G_1, ..., G_k along with the previously computed exact optimal values OPT(G_i); and
  (ii) subsequently, given a new graph H, a fast query phase must either (a) output the exact solution OPT(H), or (b) correctly report that H is not isomorphic to any G_i. Our algorithms sometimes return OPT(H) even though no graph G_i is isomorphic to H. We focus on problems Pi for which isomorphic instances yield identical optimal values, a property that holds for most natural graph problems.
  Can we avoid computing OPT(H) from scratch when H is isomorphic to some G_i? We show that this is the case for a number of problems; for many others, we establish conditional lower bounds.
  (1) NP-hard graph problems, such as Constrained and l_p-Shortest Path and Spanning Tree, admit exact algorithms with polynomial preprocessing and query times in our model. In contrast, almost all of Karp's 21 NP-complete problems, and many others, cannot be solved efficiently, or even approximately for problems such as k-center, in our model unless the Graph Isomorphism problem is in P.
  (2) In contrast to conditional n^{3-o(1)} fine-grained lower bounds, our framework achieves an O(n^omega) query time for Negative Triangle Detection and a near-linear query time for Replacement Paths. It also achieves near-linear query time for Max Flow.
  (3) While it remains a major open problem whether infinite-duration games such as Parity, Mean-Payoff, Energy, and Simple Stochastic Games admit polynomial-time algorithms, they can be easily solved in near-linear time within our model.
  Our proofs rely on a simple combination of existing tools and are easily accessible to readers unfamiliar with these methods. The primary challenge—and our main contribution—lies in identifying the right combination of models, statements, and proof techniques. We believe that this model offers a new way to explore the interplay between graph isomorphism, fine-grained complexity, and approximation algorithms, while simultaneously providing a new beyond-worst-case analysis paradigm that can guide practitioners on which structural signatures to extract from
  real-world graphs.

tags: []

url_pdf: ''

projects: []
slides: ""
---