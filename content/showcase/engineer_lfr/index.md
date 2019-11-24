---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Engineering Line Following Robot"
subtitle: ""
summary: "Investigate the Co-Simulation and DSE tools from the INTO-CPS project using LFR"
authors: []
tags: []
categories: []
date: 2018-07-03T09:00:47Z
lastmod: 2019-11-23T23:41:47Z
featured: true 
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["RoboCalc","INTO-CPS"]
---

- m3pi
{{< figure src="m3pi.png" title="[m3pi robot](https://www.pololu.com/product/2151)" numbered="true" lightbox="true" >}}

{{< figure src="lfr_math_model.jpg" title="Mathematical model of LFR" numbered="true" lightbox="true" >}}

{{< figure library="true" src="lfr/lfr_phy_model.png" title="Physical model of a line following robot in OpenModelica" lightbox="true" numbered="true">}}

- LFR running on a route with sharp corners

{{< video src="lfr_demo_sharp_corner.mp4" controls="yes" >}}

- LFR running on a map for simulation 

{{< video src="lfr_map1.mp4" controls="yes" >}}

- LFR simulation on a map

{{< video src="lfr_map1_sim.mp4" controls="yes" >}}

- DSE result 
{{< figure src="lfr_dse_result.png" title="Design space exploration results by using simulation" numbered="true" lightbox="true" >}}
