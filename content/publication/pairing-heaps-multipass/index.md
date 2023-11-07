---
title: 'Pairing heaps'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dani Dorfman
  - Haim Kaplan
  - Robert E. Tarjan
  - Uri Zwick

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2020-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *In Proc. of 31st ESA*
publication_short: In *ESA*

abstract: A weighted directed graph G = (V, A, c), naturally describes a road network in which an electric car, or vehicle (EV), can roam. An arc uv ∈ A models a road segment connecting the two vertices (junctions) u and v. The cost c(uv) of the arc uv is the amount of energy the car needs to travel from u to v. This amount can be positive, zero or negative. We consider both the more realistic scenario where there are no negative cycles in the graph, as well as the more challenging scenario, which can also be motivated, where negative cycles may be present. The electric car has a battery that can store up to B units of energy. The car can traverse an arc uv ∈ A only if it is at u and the charge b in its battery satisfies b ≥ c(uv). If the car traverses the arc uv then it reaches v with a charge of min{b − c(uv),B} in its battery. Arcs with a positive cost deplete the battery while arcs with negative costs may charge the battery, but not above its capacity of B. If the car is at a vertex u and cannot traverse any outgoing arcs of u, then it is stuck and cannot continue traveling. We consider the following natural problem- Given two vertices s, t ∈ V , can the car travel from s to t, starting at s with an initial charge b, where 0 ≤ b ≤ B? If so, what is the maximum charge with which the car can reach t? Equivalently, what is the smallest depletion δB,b(s, t) such that the car can reach t with a charge of b − δB,b(s, t) in its battery, and which path should the car follow to achieve this? We also refer to δB,b(s, t) as the energetic cost of traveling from s to t. We let δB,b(s, t) = ∞ if the car cannot travel from s to t starting with an initial charge of b. The problem of computing energetic costs is a strict generalization of the standard shortest paths problem. When there are no negative cycles, the single-source version of the problem can be solved using simple adaptations of the classical Bellman-Ford and Dijkstra algorithms. More involved algorithms are required when the graph may contain negative cycles.

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