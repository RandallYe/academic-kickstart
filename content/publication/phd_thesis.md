+++
title = "Model Checking of State-Rich Formalisms (By Linking to Combination of State-based Formalism and Process Algebra)"
date = 2016-11-25T00:00:57+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["<ins>Kangfeng Ye</ins>"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis 
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract and optional shortened version.
abstract = "Computer-based systems are becoming more and more complex. It is really a grand challenge to assure the dependability of these systems with the growing complexity, especially for high integrity and safety critical systems that require extremely high dependability. Circus, as a formal language, is designed to tackle this problem by providing precision preservation and correctness assurance. It is a combination of Z, CSP, refinement calculus and Dijkstra's guarded commands. A main objective of Circus is to provide calculational style refinement that differentiates itself from other integrated formal methods. Looseness, which is introduced from constants and uninitialised state space in Circus, and nondeterminism, which is introduced from disjunctive operations and CSP operators, make model checking of Circus more difficult than that of sole CSP or Z. Current approaches have a number of disadvantages like nondeterminism and divergence information loss, abstraction deterioration, and no appropriate tools to support automation. In this thesis, we present a new approach to model-check state-rich formalisms by linking them to a combination of a state-based formalism and a process algebra. Specifically, the approach illustrated in this thesis is to model-check Circus by linking to CSP || B. Eventually, we can use ProB, a model checker for B, Event-B, and CSP || B etc., to check the resultant CSP || B model. A formal link from Circus to CSP || B is defined in our work. Our link solution is to rewrite Circus models first to make all interactions between the state part and the behavioural part of Circus only through schema expressions, then translate the state part and the behavioural part to B and CSP respectively. In addition, since the semantics of Circus is based on Hoare and He's Unifying Theories of Programming (UTP), in order to prove the soundness of our link, we also give UTP semantics to CSP || B. Finally, because both ends of the link have their semantics defined in UTP, they are comparable. Furthermore, in order to support an automatic translation process, a translator is developed. It has supported almost all constructs defined in the link though with some limitations. Finally, three case studies are illustrated to show the usability of our model checking solution as well as limitations. The bounded reactive buffer is a typical Circus example. By our model checking approach, basic properties like deadlock freedom and divergence freedom for both the specification and the implementation with a small buffer size have been verified. In addition, the implementation has been verified to be a refinement of the specification in terms of traces and failures. Afterwards, in the Electronic Shelf Edge Label (ESEL) case study, we demonstrate how to use Circus to model different development stages of systems from the specification to two more specific systems. We have verified basic properties and sequential refinements of three models as well as three application related properties. Similarly, only the systems with a limited number of ESELs are verified. Finally, we present the steam boiler case study. It is a real and industrial control system problem. Though our solution cannot model check the steam boiler model completely due to its large state space, our solution still proves its benefits. Through our model checking approach, we have found a substantial number of errors from the original Circus solution. Then with counterexamples during animation and model checking, we have corrected all these found errors."

abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["PhD Thesis"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Circus", "CSP", "UTP", "Model Checking", "Formal Verification"]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = ""}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

The PhD thesis is available [here](http://etheses.whiterose.ac.uk/15526/7/PhD_Thesis_KangfengYe_20161112.pdf).
