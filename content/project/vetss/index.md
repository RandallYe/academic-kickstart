---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Compositional Assume-Guarantee Reasoning of Control Law Diagrams using UTP (Oct 2017 - March 2018)"
summary: "A UK National Cyber Security Centre (NCSC) funded project and we have developed a theoretical reasoning framework for discrete-time blocks of control law diagrams."
authors: []
tags: ["Unifying Theories of Programming", "UTP", "Simulink", "Formal Verification", "Theorem Prover", "Isabelle/UTP"]
categories: []
date: 2018-05-11T13:34:41+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

[This project](https://vetss.org.uk/mechanised-assume-guarantee-reasoning-for-control-law-diagrams-via-circus) is funded by VeTSS (UK Research Institute in Verified Trustworthy Software Systems). In this project, we have developed a theoretical reasoning framework for discrete-time blocks of control law diagrams. The framework is based on Hoare and He’s Unifying Theories of Programming and their theory of designs. Using UTP to give denotational semantics to block diagrams generalises the framework and makes it easily be used for another block diagrams like Modelica, or other stream based languages. In addition, our framework supports reasoning of non-deterministic and non-input-receptive systems as well as systems with algebraic loops. Particularly, we use compositional reasoning and theorem proving to tackle the state space explosion problem. 

In terms of outcomes, we developed 

- a theoretical reasoning framework for the discrete-time part of control law block diagrams (such as Simulink) using theorem proving (based on the mathematical semantics of diagrams and capable of dealing with large state spaces)

it supports 

- contract-based compositional reasoning (using refinement relation) to tackle verification of large systems

it is 

- able to reason and resolve diagrams with algebraic loops (ignored by most verification approaches)

and we have 

- verified one subsystem of an aircraft cabin pressure control application (from industry)


{{< figure src="vetss_isabelle.png" title="Isabelle/UTP based verification" >}}

More information could be found in the technical [report](http://eprints.whiterose.ac.uk/129640/).
