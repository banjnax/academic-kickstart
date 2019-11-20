---
title: "Mechanism Design in Social Networks"
authors:
- admin
- Dong Hao
- Dengji Zhao
- Tao Zhou
date: "2017-02-9"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-02-9"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *the 31st AAAI Conference on Artificial Intelligence*
publication_short: In *AAAI17*

abstract: This paper studies an auction design problem for a seller to sell a commodity in a social network, where each individual (the seller or a buyer) can only communicate with her neighbors. The challenge to the seller is to design a mechanism to incentivize the buyers, who are aware of the auction, to further propagate the information to their neighbors so that more buyers will participate in the auction and hence, the seller will be able to make a higher revenue. We propose a novel auction mechanism, called information diffusion mechanism (IDM), which incentivizes the buyers to not only truthfully report their valuations on the commodity to the seller, but also further propagate the auction information to all their neighbors. In comparison, the direct extension of the well-known Vickrey-Clarke-Groves (VCG) mechanism in social networks can also incentivize the information diffusion, but it will decrease the seller's revenue or even lead to a deficit sometimes. The formalization of the problem has not yet been addressed in the literature of mechanism design and our solution is very significant in the presence of large-scale online social networks.

# Summary. An optional shortened abstract.
summary: This paper studies an auction design problem for a seller to sell a commodity in a social network, where each individual (the seller or a buyer) can only communicate with her neighbors.

tags:
- Conferences
featured: false

links:
- name: paper
  url: 'aaai17/liaaai17.pdf'
- name: slide
  url: 'aaai17/ppt.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---