---
title: 'Pairing heaps: the forward variant'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dani Dorfman
  - Haim Kaplan
  - Laszlo Kozma
  - Uri Zwick

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2018-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *MFCS*
publication_short: In *MFCS*

abstract: The pairing heap is a classical heap data structure introduced in 1986 by Fredman, Sedgewick, Sleator, and Tarjan. It is remarkable both for its simplicity and for its excellent performance in practice. The “magic” of pairing heaps lies in the restructuring that happens after the deletion of the smallest item. The resulting collection of trees is consolidated in two rounds&colon; a left-to-right pairing round, followed by a right-to-left accumulation round. Fredman et al. showed, via an elegant correspondence to splay trees, that in a pairing heap of size n all heap operations take O(log n) amortized time. They also proposed an arguably more natural variant, where both pairing and accumulation are performed in a combined left-to-right round (called the forward variant of pairing heaps). The analogy to splaying breaks down in this case, and the analysis of the forward variant was left open. In this paper we show that inserting an item and deleting the minimum in a forward-variant pairing heap both take amortized time O(log n · 4^&radic;(log n)). This is the first improvement over the O(&radic;(n)) bound showed by Fredman et al. three decades ago. Our analysis relies on a new potential function that tracks parent-child rank-differences in the heap.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
#featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---