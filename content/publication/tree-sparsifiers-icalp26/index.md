---
title: 'Improved Tree Sparsifiers in Near-Linear Time'

authors:
  - Daniel Agassy
  - Dani Dorfman
  - Haim Kaplan

date: '2026-07-01T00:00:00Z'
doi: ''

publishDate: '2026-07-01T00:00:00Z'

publication_types: ['paper-conference']

publication: In *ICALP*
publication_short: In *ICALP*

abstract: A tree cut-sparsifier T of quality α of a graph G is a single tree that preserves the capacities of all cuts in the graph up to a factor of α. A tree flow-sparsifier T of quality α guarantees that every demand that can be routed in T can also be routed in G with congestion at most α. We present a near-linear time algorithm that, for any undirected capacitated graph G = (V,E,c), constructs a tree cut-sparsifier T of quality O(log² n log log n), where n = |V|. This nearly matches the quality of the best known polynomial construction of a tree cut-sparsifier, of quality O(log^{1.5} n log log n). By the flow-cut gap, our result yields a tree
  flow-sparsifier (and congestion-approximator) of quality O(log³ n log log n). This improves on the celebrated result of Räcke, Shah, and Täubig (SODA 2014) that gave a near-linear time construction of a tree flow-sparsifier of quality O(log⁴ n). Our algorithm builds on a recent expander decomposition algorithm by Agassy, Dorfman, and Kaplan (ICALP 2023), which we use as a black box to obtain a clean and modular foundation for tree cut-sparsifiers. This yields an improved and simplified version of the RST construction for cut-sparsifiers with quality O(log³ n). We then introduce a near-linear time refinement phase that controls the load
  accumulated on boundary edges of the sub-clusters across the levels of the tree. Combining the improved framework with this refinement phase leads to our final O(log² n log log n) tree cut-sparsifier.

tags: []

url_pdf: ''

url_slides: "tree-sparsifiers-icalp26.pptx"


projects: []
slides: ""
---