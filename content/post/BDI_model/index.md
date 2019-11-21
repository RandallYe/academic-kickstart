---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Belief-Desire-Intention (BDI)"
subtitle: "A model that is mentioned in Prof. Kerstin Eder and Prof. Michael Fisher's talks in RoboSoft"
summary: "BDI is new to me and better to know a bit about it."
authors: []
tags: []
categories: []
date: 2019-11-13T14:24:11Z
lastmod: 2019-11-13T14:24:11Z
featured: false
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
projects: []
---

### Terms
**Beliefs**: facts that an agent believes about the world, like knowledge. But it is not necessary to be always true.

**Desires**: are goals and preferred end states. An agent may have many desires, possibly in conflict.

**Intentions**: are the agent's _commitments_ to its desire. They shall be consistent and without conflict.

**Rational Agents**:

> A rational agent is an agent that has clear _preferences_, models _uncertainty_ via expected values of variables or functions of variables, and always chooses to perform the action with the _optimal_ expected outcome for itself from among all feasible actions. A rational agent can be _anything that makes decisions_, typically a person, firm, machine, or software. (Wikipedia)

### Some statements
> Intentions are fundamentally based on the notion of commitments

> Commitments relate to _satisficing_ (good enough), and _optimal_ to the _best_ solution

> Intentions are meant to stabilize decision making (Bratman)

### BDI logics

- Cohen and Levesque logic
- Rao and Georgeff’s belief-desire-intention logic

### BDI Architecture
- _Belief store_
- _Goal store_
- _Plan-library_
- _Intention hierarchy_

### Applications
- BDI agent models for test generation ([Prof. Kerstin Eder](http://www.bris.ac.uk/engineering/people/kerstin-i-eder/index.html))
    + BDI agents vs. automata for model-based test generation (see "Model-based Test Generation for Robotic Software:Automata versus Belief-Desire-Intention Agents")

### References:
- M. E. **Bratman**. Intention, plans, and practical reason. Harvard University Press, Cambridge Massachusetts, 1987
- "Modeling rational agents within a BDI architecture" by Rao and Georgeff
- "BDI Agents: From Theory to Practice" by Rao and Georgeff
- "The Belief-Desire-Intention Model of Agency" by Michael Georgeff et. al
- "CHAPTER 2: Beliefs, Desires, Intentions (BDI Logic)" by Milind Tambe
- P. Cohen and H. Levesque. Intention is choice with commitment. _Artificial Intelligence_, 42(2-3):213–261, 1990
- "AgentSpeak(L): BDI Agents speak out in a logicalcomputable language" by Rao regarding BDI architectures
