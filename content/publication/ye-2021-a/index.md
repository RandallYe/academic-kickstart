---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Automated Reasoning for Probabilistic Sequential Programs with Theorem Proving
subtitle: ''
summary: ''
authors:
- "<ins>Kangfeng Ye</ins>"
- Simon Foster
- Jim Woodcock
tags: []
categories: []
date: '2021-10-22'
lastmod: 2021-11-05T20:56:16Z
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
publishDate: '2021-10-22T20:56:16.062057Z'
publication_types:
- '1'
abstract: Semantics for nondeterministic probabilistic sequential programs has been
  well studied in the past decades. In a variety of semantic models, how nondeterministic
  choice interacts with probabilistic choice is the most significant difference. In
  He, Morgan, and McIver's relational model, probabilistic choice refines nondeterministic
  choice. This model is general because of its predicative-style semantics in Hoare
  and He's Unifying Theories of Programming, and suitable for automated reasoning
  because of its algebraic feature. Previously, we gave probabilistic semantics to
  the RoboChart notation based on this model, and also formalised the proof that the
  semantic embedding is a homomorphism, and revealed interesting details. In this
  paper, we present our mechanisation of the proof in Isabelle/UTP enabling automated
  reasoning for probabilistic sequential programs including a subset of the RoboChart
  language. With mechanisation, we even reveal more interesting questions, hidden
  in the original model. We demonstrate several examples, including an example to
  illustrate the interaction between nondeterministic choice and probabilistic choice,
  and a RoboChart model for randomisation based on binary probabilistic choice.
publication: '*Relational and Algebraic Methods in Computer Science*'
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-88701-8_28.pdf
doi: https://doi.org/10.1007/978-3-030-88701-8_28
---
