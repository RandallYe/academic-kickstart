---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Animation of RoboChart with Interaction Trees"
event: "RoboStar group meeting"
event_url: "https://www.cs.york.ac.uk/robostar/seminars/#"
location: "Online"
address:
  street:
  city:
  region:
  postcode:
  country:
summary: "Animation of RoboChart using Interaction Trees based CSP and code generation in Isabelle"

abstract: "Recent mechanisations of Interaction Trees (ITrees) along with ITrees-based CSP semantics and a Z mathematical toolkit in Isabelle/HOL bring new applications of verification and simulation for state-rich process languages. The formal semantics of RoboChart, a timed and probabilistic domain-specific and state machines based language for robotics, is such a language. RoboChart supports shared variables and communication across entities in its component model. Its core semantics is given in CSP. In this paper we implement RoboChart’s core semantics in ITrees-based CSP in Isabelle and use Isabelle’s code generator to generate a verified and executable animation for RoboChart. We illustrate our approach using an autonomous chemical detector example. With animation we show two concrete scenarios when the robot encounters different environment inputs."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-10-06T10:50:00Z
date_end: 2021-10-06T11:30:00Z
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-09-12T09:00:00Z

authors: []
tags: ["RoboChart", "Animation", "Verification", "Theorem Proving", "Isabelle", "Z", "Interaction Trees"]

# Is this a featured talk? (true/false)
featured: false 

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
projects: ["CyPhyAssure"]
---
