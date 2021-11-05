---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Automated Reasoning for Probabilistic Sequential Programs with Theorem Proving"
event: "RAMiCS2021"
event_url: "https://ramics19.lis-lab.fr/"
location: "Online"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "Presentation for RAMiCS2021"

abstract: "
Semantics for nondeterministic probabilistic sequential pro- grams has been well studied in the past decades. In a variety of semantic models, how nondeterministic choice interacts with probabilistic choice is the most significant difference. In He, Morgan, and McIver’s relational model, probabilistic choice refines nondeterministic choice. This model is general because of its predicative-style semantics in Hoare and He’s Unifying Theories of Programming, and suitable for automated reasoning because of its algebraic feature. Previously, we gave probabilistic semantics to the RoboChart notation based on this model, and also formalised the proof that the semantic embedding is a homomorphism, and revealed interesting details. In this paper, we present our mechanisation of the proof in Isabelle/UTP enabling automated reasoning for probabilistic sequential programs including a subset of the RoboChart language. With mechanisation, we even reveal more interesting questions, hidden in the original model. We demonstrate several examples, including an ex- ample to illustrate the interaction between nondeterministic choice and probabilistic choice, and a RoboChart model for randomisation based on binary probabilistic choice.
"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-11-04T11:00:00Z
date_end: 2021-11-04T11:30:00Z
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-10-22T09:00:00Z

authors: []
tags: ["RoboChart", "Verification", "Theorem Proving", "Isabelle", "Probabilistic", "UTP", "Formal semantics", "Mechanisation"]

# Is this a featured talk? (true/false)
featured: true 

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

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["RoboCalc"]
---
