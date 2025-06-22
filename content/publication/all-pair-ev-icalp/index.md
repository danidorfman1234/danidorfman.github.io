---
title: 'Faster All-Pairs Optimal Electric Car Routing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dani Dorfman
  - Haim Kaplan
  - Robert E. Tarjan
  - Mikkel Thorup
  - Uri Zwick

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-06-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ICALP*
publication_short: In *ICALP*

abstract: We present a randomized  ̃O(n3.5)-time algorithm for computing optimal energetic paths for an electric car between all pairs of vertices in an n-vertex directed graph with positive and negative costs, or gains, which are defined to be the negatives of the costs. The optimal energetic paths are finite and well-defined even if the graph contains negative-cost, or equivalently, positive-gain, cycles. This makes the problem much more challenging than standard shortest paths problems. More specifically, for every two vertices s and t in the graph, the algorithm computes αB (s, t), the maximum amount of charge the car can reach t with, if it starts at s with full battery, i.e., with charge B, where B is the capacity of the battery. The algorithm also outputs a concise description of the optimal energetic paths that achieve these values. In the presence of positivegain cycles, optimal paths are not necessarily simple. For dense graphs, our new  ̃O(n3.5) time algorithm improves on a previous  ̃O(mn2)-time algorithm of Dorfman et al. [ESA 2023] for the problem. The gain of an arc is the amount of charge added to the battery of the car when traversing the arc. The charge in the battery can never exceed the capacity B of the battery and can never be negative. An arc of positive gain may correspond, for example, to a downhill road segment, while an arc with a negative gain may correspond to an uphill segment. A positive-gain cycle, if one exists, can be used in certain cases to charge the battery to its capacity. This makes the problem more interesting and more challenging. As mentioned, optimal energetic paths are well-defined even in the presence of positive-gain cycles. Positive-gain cycles may arise when certain road segments have magnetic charging strips, or when the electric car has solar panels. Combined with a result of Dorfman et al. [SOSA 2024], this also provides a randomized  ̃O(n3.5)time algorithm for computing minimum-cost paths between all pairs of vertices in an n-vertex graph when the battery can be externally recharged, at varying costs, at intermediate vertices.

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

url_slides: "all-pairs-icalp25.pptx"

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---