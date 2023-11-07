---
title: 'Minimum-cost paths for electric cars'

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

date: '2024-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Symposium on Simplicity in Algorithms (SOSA)*
publication_short: In *SOSA*

abstract: An electric car equipped with a battery of a finite capacity travels on a road network with an infrastructure of charging stations. Each charging station has a possibly different cost per unit of energy. Traversing a given road segment requires a specified amount of energy that may be positive, zero or negative. The car can only traverse a road segment if it has enough charge to do so (the charge cannot drop below zero), and it cannot charge its battery beyond its capacity. To travel from one point to another the car needs to choose a travel plan consisting of a path in the network and a recharging schedule that specifies how much energy to charge at each charging station on the path, making sure of having enough energy to reach the next charging station or the destination. The cost of the plan is the total charging cost along the chosen path. We reduce the problem of computing plans between every two junctions of the network to two problems- Finding optimal energetic paths when no charging is allowed and finding standard shortest paths. When there are no negative cycles in the network, we obtain an O(n3)-time algorithm for computing all-pairs travel plans, where n is the number of junctions in the network. We obtain slightly faster algorithms under some further assumptions. We also consider the case in which a bound is placed on the number of rechargings allowed.

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