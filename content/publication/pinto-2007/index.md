---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Ranked adjusted rand: Integrating distance and partition information in a
  measure of clustering agreement'
subtitle: ''
summary: ''
authors:
- F. R. Pinto
- J. A. Carriço
- M. Ramirez
- J. S. Almeida
tags: []
categories: []
date: '2007-01-01'
lastmod: 2023-02-02T15:20:14Z
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
publishDate: '2023-02-02T15:26:06.771267Z'
publication_types:
- '2'
abstract: 'Background: Biological information is commonly used to cluster or classify
  entities of interest such as genes, conditions, species or samples. However, different
  sources of data can be used to classify the same set of entities and methods allowing
  the comparison of the performance of two data sources or the determination of how
  well a given classification agrees with another are frequently needed, especially
  in the absence of a universally accepted \"gold standard\" classification. Results:
  Here, we describe a novel measure - the Ranked Adjusted Rand (RAR) index. RAR differs
  from existing methods by evaluating the extent of agreement between any two groupings,
  taking into account the intercluster distances. This characteristic is relevant
  to evaluate cases of pairs of entities grouped in the same cluster by one method
  and separated by another. The latter method may assign them to close neighbour clusters
  or, on the contrary, to clusters that are far apart from each other. RAR is applicable
  even when intercluster distance information is absent for both or one of the groupings.
  In the first case, RAR is equal to its predecessor, Adjusted Rand (HA) index. Artificially
  designed clusterings were used to demonstrate situations in which only RAR was able
  to detect differences in the grouping patterns. A study with larger simulated clusterings
  ensured that in realistic conditions, RAR is effectively integrating distance and
  partition information. The new method was applied to biological examples to compare
  1) two microbial typing methods, 2) two gene regulatory network distances and 3)
  microarray gene expression data with pathway information. In the first application,
  one of the methods does not provide intercluster distances while the other originated
  a hierarchical clustering. RAR proved to be more sensitive than HA in the choice
  of a threshold for defining clusters in the hierarchical method that maximizes agreement
  between the results of both methods. Conclusion: RAR has its major advantage in
  combining cluster distance and partition information, while the previously available
  methods used only the latter. RAR should be used in the research problems were HA
  was previously used, because in the absence of inter cluster distance effects it
  is an equally effective measure, and in the presence of distance effects it is a
  more complete one. © 2007 Pinto et al; licensee BioMed Central Ltd.'
publication: '*BMC Bioinformatics*'
doi: 10.1186/1471-2105-8-44
---
