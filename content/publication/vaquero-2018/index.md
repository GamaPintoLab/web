---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Searching the overlap between network modules with specific betweeness (S2B)
  and its application to cross-disease analysis
subtitle: ''
summary: ''
authors:
- M. L. Garcia-Vaquero
- M. Gama-Carvalho
- J. D. L. Rivas
- F. R. Pinto
tags: []
categories: []
date: '2018-01-01'
lastmod: 2023-02-03T10:41:03Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-02-03T10:41:01.758798Z'
publication_types:
- '2'
abstract: © 2018, The Author(s). Discovering disease-associated genes (DG) is strategic
  for understanding pathological mechanisms. DGs form modules in protein interaction
  networks and diseases with common phenotypes share more DGs or have more closely
  interacting DGs. This prompted the development of Specific Betweenness (S2B) to
  find genes associated with two related diseases. S2B prioritizes genes frequently
  and specifically present in shortest paths linking two disease modules. Top S2B
  scores identified genes in the overlap of artificial network modules more than 80%
  of the times, even with incomplete or noisy knowledge. Applied to Amyotrophic Lateral
  Sclerosis and Spinal Muscular Atrophy, S2B candidates were enriched in biological
  processes previously associated with motor neuron degeneration. Some S2B candidates
  closely interacted in network cliques, suggesting common molecular mechanisms for
  the two diseases. S2B is a valuable tool for DG prediction, bringing new insights
  into pathological mechanisms. More generally, S2B can be applied to infer the overlap
  between other types of network modules, such as functional modules or context-specific
  subnetworks. An R package implementing S2B is publicly available at https://github.com/frpinto/S2B.
publication: '*Scientific Reports*'
doi: 10.1038/s41598-018-29990-7
---
