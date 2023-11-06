---
title: 'Optimal energetic paths for electric cars'

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

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ESA*
publication_short: In *ESA*

abstract: A weighted directed graph G=(V,A,c), where A⊆V×V and c:A→R, describes a road network in which an electric car can roam. An arc uv models a road segment connecting the two vertices u and v. The cost c(uv) of an arc uv is the amount of energy the car needs to traverse the arc. This amount may be positive, zero or negative. To make the problem realistic, we assume there are no negative cycles.
The car has a battery that can store up to B units of energy. It can traverse an arc uv∈A only if it is at u and the charge b in its battery satisfies b≥c(uv). If it traverses the arc, it reaches v with a charge of min(b−c(uv),B). Arcs with positive costs deplete the battery, arcs with negative costs charge the battery, but not above its capacity of B.
Given s,t∈V, can the car travel from s to t, starting at s with an initial charge b, where 0≤b≤B? If so, what is the maximum charge with which the car can reach t? Equivalently, what is the smallest δB,b(s,t) such that the car can reach t with a charge of b−δB,b(s,t), and which path should the car follow to achieve this? We refer to δB,b(s,t) as the energetic cost of traveling from s to t. We let δB,b(s,t)=∞ if the car cannot travel from s to t starting with an initial charge of b. The problem of computing energetic costs is a strict generalization of the standard shortest paths problem.
We show that the single-source minimum energetic paths problem can be solved using simple, but subtle, adaptations of the Bellman-Ford and Dijkstra algorithms. To make Dijkstra's algorithm work in the presence of negative arcs, but no negative cycles, we use a variant of the A∗ search heuristic. These results are explicit or implicit in some previous papers. We provide a simpler and unified description of these algorithms.

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
url_slides: ''
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
