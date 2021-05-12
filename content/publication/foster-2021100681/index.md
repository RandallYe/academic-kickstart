---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Automated verification of reactive and concurrent programs by calculation
subtitle: ''
summary: ''
authors:
- Simon Foster
- "<ins>Kangfeng Ye</ins>"
- Ana Cavalcanti
- Jim Woodcock
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-05-12T20:00:54+01:00
featured: true
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
publishDate: '2021-05-12T19:00:53.681248Z'
publication_types:
- '2'
abstract: Reactive programs combine traditional sequential programming constructs
  with primitives to allow communication with other concurrent agents. They are ubiquitous
  in modern applications, ranging from components systems and web services, to cyber-physical
  systems and autonomous robots. In this paper, we present an algebraic verification
  strategy for concurrent reactive programs, with a large or infinite state space.
  We define novel operators to characterise interactions and state updates, and an
  associated equational theory. With this we can calculate a reactive program's denotational
  semantics, and thereby facilitate automated proof. Of note is our reasoning support
  for iterative programs with reactive invariants, based on Kleene algebra, and for
  parallel composition. We illustrate our strategy by verifying a reactive buffer.
  Our laws and strategy are mechanised in Isabelle/UTP, our implementation of Hoare
  and He's Unifying Theories of Programming (UTP) framework, to provide soundness
  guarantees and practical verification support.
publication: '*Journal of Logical and Algebraic Methods in Programming*'
url_pdf: https://www.sciencedirect.com/science/article/pii/S2352220821000444
doi: https://doi.org/10.1016/j.jlamp.2021.100681
---
