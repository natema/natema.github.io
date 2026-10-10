+++
title = "Software"
+++

## graph-theory-AI

[graph-theory-AI](https://github.com/graph-theory-AI) is an open organisation, started in 2026, that applies large language models to open problems in graph theory.
Its main projects are:

* **[Mathpocalypse](https://github.com/graph-theory-AI/mathpocalypse-project)** *(lead)*.
  A pilot study testing whether an open-weight language model, run only on public research computers, can find genuine errors in published mathematics.
  The model rereads papers in graph theory and combinatorics and flags steps that may be wrong; each serious flag is re-checked before the authors are contacted.
  Several research groups have updated their arXiv papers to acknowledge the project.
  [DOI: 10.5281/zenodo.21499917](https://doi.org/10.5281/zenodo.21499917)
* **[Graph Theory LLM Proofs](https://github.com/graph-theory-AI/Graph-Theory-LLM-Proofs)** *(co-lead)*.
  Proof attempts by frontier models on the open problems collected in Graph Conjectures; each claimed resolution is checked by a second model before reaching human referees.
  Several proofs have been confirmed by mathematicians.
* **[Graph Conjectures](https://github.com/graph-theory-AI/graph-conjectures)**.
  A browsable mirror of the graph-theory problems of [Open Problem Garden](http://www.openproblemgarden.org/category/graph_theory), annotated with their current status and extended with conjectures from recent arXiv papers.

## Leanamycs

[Leanamycs](https://formal-dynamics.github.io/leanamycs/) is a Lean 4 library of formally verified results on opinion dynamics and related processes: rumor spreading, voter and Moran processes, epidemics, averaging, etc.
AI agents formalize the statements and the published proofs from the original papers, and Lean checks every step; a blueprint links each formal result to the paper proof it comes from.
The project is at an early stage, and contributions are welcome through its [roadmap](https://github.com/formal-dynamics/leanamics/blob/main/ROADMAP.md).

## Older projects

* **[WorldDynamics.jl](https://github.com/worlddynamics/WorldDynamics.jl)** (2021–2024).
  An open-source Julia framework for global integrated assessment models, which reimplements the World1–World3 models in a modular way ([JOSS 2024](https://joss.theoj.org/papers/10.21105/joss.05772)).
  We built on it the [Earth4All.jl](https://github.com/worlddynamics/Earth4All.jl) implementation of the Earth for All model, and used it for a sensitivity analysis of that model ([JIE 2024](https://onlinelibrary.wiley.com/doi/10.1111/jiec.13582)).
* **[KADABRA](https://github.com/natema/kadabra)** (2016).
  An adaptive sampling algorithm for approximating betweenness centrality in large networks ([ESA 2016](https://drops.dagstuhl.de/opus/volltexte/2016/6371/), [JEA 2019](https://dl.acm.org/doi/10.1145/3284359)), with Michele Borassi.
  It is included in [NetworKit](https://networkit.github.io/) since version 5.0.

## Other code

More of my code is on [my GitHub page](https://github.com/natema).
