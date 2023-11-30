---
title: 'A faster deterministic exponential time algorithm
for Energy Games and Mean Payoff Games'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dani Dorfman
  - Haim Kaplan
  - Uri Zwick

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2019-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Colloquium on Automata, Languages, and Programming (ICALP 2019)
publication_short: In *ICALP*

abstract: We present an improved exponential time algorithm for Energy Games, and hence also for Mean
Payoff Games. The running time of the new algorithm is O(min(mnW, m 2^{n/2})), where n is the
number of vertices, m is the number of edges, and when the edge weights are integers of absolute value
at most W. For small values of W, the algorithm matches the performance of the pseudopolynomial
time algorithm of Brim et al., on which it is based. For W &ge; 2^{n/2}, the new algorithm is faster than
the algorithm of Brim et al. and is currently the fastest deterministic algorithm for Energy Games
and Mean Payoff Games. The new algorithm is obtained by introducing a technique of forecasting
repetitive actions performed by the algorithm of Brim et al.

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