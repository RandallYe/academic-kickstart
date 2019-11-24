---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Engineering Line Following Robot"
subtitle: "Investigate the Co-Simulation and DSE tools from the [INTO-CPS](https://into-cps.org/) project using LFR."
summary: "The map shown on the right is a Formula One circuit: [Brands_Hatch](https://en.wikipedia.org/wiki/Brands_Hatch) that I use to run my LFR experience."
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

**Motivations**: I used to work in the [INTO-CPS](https://into-cps.org/) project and had experience in model-based design and test of several pilot studies, including line following robots. Co-Simulation was also used to test and verify models with heterogeneous modules being wrapped in individual FMUs. When I started to work in the [RoboCalc](https://www.cs.york.ac.uk/circus/RoboCalc/) project, a [RoboStar](https://www.cs.york.ac.uk/robostar/) project. Prof. [Jim Woodcock](https://www-users.cs.york.ac.uk/~jim/) and Prof. [Ana Cavalcanti](https://www-users.cs.york.ac.uk/~alcc/) thought we should build a simple physical LFR robot (but faster) and demonstrate INTO-CPS's technologies. Most importantly, it could be as a case study for formal verification, such as theorem proving to ensure the control algorithm of LFR can cope with sharp bends when it is running very fast. It was a pity that later on we haven't moved forward to formal verification (because I turned to investigate the probabilistic aspect of RoboChart).  

{{< figure src="m3pi.png" title="[m3pi robot](https://www.pololu.com/product/2151)" numbered="true" lightbox="true" >}}

{{< figure src="lfr_math_model.jpg" title="Mathematical model of LFR" numbered="true" lightbox="true" >}}

{{< figure library="true" src="lfr/lfr_phy_model.png" title="Physical model of a line following robot in OpenModelica" lightbox="true" numbered="true">}}

{{% staticref "files/lfr/my_lfr_gcc_20180807.zip" "newtab" %}}My controller code (C++){{% /staticref %}}: I have borrowed some ideas from this paper ["Optimization of PID Control for High Speed Line Tracking Robots"](https://doi.org/10.1016/j.procs.2015.12.329) 

- LFR running on a route with sharp corners

{{< video src="lfr_demo_sharp_corner.mp4" controls="yes" >}}

- LFR running on a map for simulation 

{{< video src="lfr_map1.mp4" controls="yes" >}}

- LFR simulation on a map

{{< video src="lfr_map1_sim.mp4" controls="yes" >}}

- DSE result 
{{< figure src="lfr_dse_result.png" title="Design space exploration results by using simulation" numbered="true" lightbox="true" >}}

- References: 
    + [INTO-CPS Examples Compendium](https://github.com/INTO-CPS-Association/Documentation/blob/master/examples_compendium/INTO-CPS_Examples_Compendium.pdf) (I am also a contributor of the document)
