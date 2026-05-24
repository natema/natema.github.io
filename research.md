
+++
title = "Research"


tags = ["syntax", "code"]
+++

## Recent projects

* **ELECTRON joint team between INRIA UniCA and KCL** *(2025-2027)*
  Team leader of the [ELECTRON INRIA joint team](https://team.inria.fr/electron/) with King's College London.
* **BioSwarm Project - DGA** *(November 2023 – 2027)*
  Principal investigator of a 4-year national research project on algorithms for coordination tasks in drone swarms, funded by the DGA (the French Government Defence procurement and technology agency).

## Group members

### Post-docs & Research Engineers

* [Maria Sofia Bucarelli](), Post-doc (3IA), 2026 — 2027.
* [Hamidou Diallo](), Research Engineer (INSA Lyon, with Olivier Simonin), 2025 — 2027.
* [Damien Rivet](), Post-doc (INRIA UCA), 2022 — 2023.
* [Paulo Bruno Serafim](https://paulobruno.github.io/), Research Engineer (INRIA UCA), 2022.
* [Emilio Cruciani](https://sites.google.com/view/emiliocruciani/), Post-doc (I3S), 2019 — 2020.

### PhD Students

* [Matteo Stromieri](https://matteostromieri.github.io/) (UCA), 2025 — 2028 (expected).
* [Carlo Castoldi]() (UCA), 2025 — 2028 (expected).
* [Aakash Kumar](https://aakash-verse.github.io/) (UCA), 2025 — 2028 (expected).
* [Pierre Pereira](https://pierrot-lc.dev/) (UCA), 2024 — 2027 (expected).
* [Niccolò D'Archivio](https://sites.google.com/view/niccolo-darchivio/home) (UCA), 2024 — 2027 (expected).
* [Davide Ferre](https://dferre97.github.io/) (UCA), 2024 — 2026 (expected).
* [Arthur Carvalho Walraven Da Cunha](https://arthurwalraven.github.io/) (UCA), 2020 — 2023.
* [Francesco D'Amore](https://fdamore95.github.io/) (UCA), 2019 — 2022.
* [Emilio Cruciani](https://sites.google.com/view/emiliocruciani/) (Gran Sasso Science Institute), 2016 — 2019.

## Research Bio

My research studies how global behavior emerges from systems made of many simple interacting units, and how this viewpoint can be used to design algorithms, explain collective behavior, and understand efficient learning.
Across theoretical computer science, machine learning, and computational neuroscience, I try to identify the minimal local rules, randomness, memory, communication, or structure needed for a system to compute reliably.

### Learning theory and efficient machine learning

Since 2019, a central part of my work has been the mathematical theory of neural network sparsification.
In the line of work around the Lottery Ticket and Strong Lottery Ticket hypotheses, I have studied when large random networks contain subnetworks that approximate trained or target networks, including convolutional architectures and structured winning tickets ([LTH22], [SLTH23], [RSS23]).
More recently, I have been investigating the sharp limits of this phenomenon: how sparsity scales in strong lottery tickets ([SSLT24]), what changes under finite precision and quantization ([QuantPrune26]), and why structured neuron pruning can be exponentially less expressive than unstructured weight pruning ([NeuronPrune26]).

I have also worked on algorithmic machine learning beyond pruning.
This includes graph neural networks for scalable betweenness ranking on difficult network families ([BRAVA26]), transformer-based neural solvers for the Euclidean Traveling Salesman Problem using positional encodings ([TSPPosEnc26]), communication-efficient federated learning ([FedLSF25], [GENE25]), GPU implementations of FlyHash ([CAID23]), hidden learning and information leakage in neural networks ([HID23]), and scheduling models for neural inference with fully compressible tasks ([SCHED24]).
From 2021 to 2024, I also contributed to scientific computing tools for integrated assessment modeling in Julia, including the WorldDynamics.jl package and sensitivity analysis of the Earth for All model ([JOSS24], [JIE24]).

### Computational neuroscience and brain networks

Since 2017, I have been interested in theoretical and computational neuroscience, starting with my fellowship in the [Brain and Computation Program of the Simons Institute for the Theory of Computing](https://simons.berkeley.edu/programs/brain2018).
A recurring goal has been to bring algorithmic and network-science tools to questions about how nervous systems are organized and how they compute.
On brain data, I have worked on network-alignment methods for comparing structural connectomes across brain atlases ([BrainAlign21]), temporal null models for small-world structure in fMRI dynamics ([Hyper24]), and Shapley-value methods for identifying functional-connectivity subnetworks that contribute to narrative classification ([ShapFMRI25]).
On the theory side, I have worked on the Assembly Calculus as a model of high-level cognition emerging from Hebbian-style neural and synaptic dynamics ([AC22]).

### Distributed computation and collective behavior

My original research program is in computational dynamics: simple randomized protocols by which a population of small agents solves global coordination tasks ([CompDyn17], [SurvDyn20]).
The central question is not only whether these dynamics eventually compute, but how fast, robustly, and with how little memory or communication they do so.
I have studied consensus, plurality consensus, and rumor spreading under constraints such as noise, adversarial perturbations, many opinions, self-stabilization, and tiny messages ([StabCons16], [UndDyn15], [SimpleDyn17], [NoisCons19], [NoisyUnd20], [NoisyPull26], [DejaVu26], [ConsBroad20], [MinMsg19]).
A complementary line of work analyzes how the same simple dynamics can perform distributed clustering or expose network structure, including dynamic stochastic block models, metastability of the 2-Choices dynamics, and community-detection protocols based on local averaging or label propagation ([DistCom15], [MetaStab19], [PPComDet18], [FYPComDet20], [PhaseTrans18]).

This perspective also connects to biological distributed algorithms.
I have studied limits on reliable information flow in noisy populations ([InfoFlow18]), models of noisy collective decision-making ([Swarm22]), collective dynamics inspired by Physarum's ability to estimate electrical flows ([DistFlow18]), and search by parallel Lévy walks ([Levy22], [Levy3D26]).
More broadly, I have worked on population protocols for order statistics ([OrderStats26]), stochastic load balancing and balls-into-bins processes ([RepBins19], [ParLoad20]), dynamic expander extraction and rumor spreading under churn ([DistSparse20], [RAES26]), fast approximation algorithms for betweenness centrality ([Kadabra19]), and the complexity of combinatorial games and puzzles ([Candy14], [PegS16], [CoG]).

## Code

You can find some of my code on [my Github page](https://github.com/natema).

## Misc

Here's
~~~
<a href="https://genealogy.math.ndsu.nodak.edu/id.php?id=238289">my Mathematics Genealogy Project page</a>.
~~~
My Erdős number is 3, thanks to Giorgio Gambosi.


[CNRS]: https://www.cnrs.fr
[COATI]: https://team.inria.fr/coati/team-members
[CoG]: https://gitlab.com/steven3k/complexity-of-games
[I3S]: http://www.i3s.unice.fr
[INRIA]: https://www.inria.fr
[UCA]: http://univ-cotedazur.fr
[Candy14]: https://ieeexplore.ieee.org/document/6932866
[DistCom15]: https://www.sciencedirect.com/science/article/pii/S0304397514009402?via%3Dihub
[UndDyn15]: https://epubs.siam.org/doi/10.1137/1.9781611973730.27
[PegS16]: https://drops.dagstuhl.de/opus/volltexte/2016/5870/
[StabCons16]: https://epubs.siam.org/doi/10.1137/1.9781611974331.ch46
[CompDyn17]: https://tel.archives-ouvertes.fr/tel-02002681
[IgnComp17]: https://dl.acm.org/doi/10.1145/3087801.3087817
[SimpleDyn17]: https://link.springer.com/article/10.1007%2Fs00446-016-0289-4
[DistFlow18]: https://dl.acm.org/doi/10.5555/3237383.3237935
[InfoFlow18]: https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006195
[PhaseTrans18]: https://dl.acm.org/doi/10.5555/3237383.3237499
[PPComDet18]: https://drops.dagstuhl.de/opus/volltexte/2018/9470/
[Kadabra19]: https://dl.acm.org/doi/10.1145/3284359
[MetaStab19]: https://ojs.aaai.org//index.php/AAAI/article/view/4560
[MinMsg19]: https://link.springer.com/article/10.1007%2Fs00446-018-0330-x
[NoisCons19]: https://link.springer.com/article/10.1007%2Fs00446-018-0335-5
[RepBins19]: https://link.springer.com/article/10.1007%2Fs00446-017-0320-4
[ConsBroad20]: https://drops.dagstuhl.de/opus/volltexte/2020/11727/
[DistSparse20]: https://epubs.siam.org/doi/10.1137/1.9781611975994.80
[FYPComDet20]: https://epubs.siam.org/doi/10.1137/19M1243026
[NoisyUnd20]: https://link.springer.com/chapter/10.1007%2F978-3-030-54921-3_15
[ParLoad20]: https://dl.acm.org/doi/10.1145/3350755.3400232
[SurvDyn20]: https://dl.acm.org/doi/10.1145/3388392.3388403
[BrainAlign21]: https://hal.archives-ouvertes.fr/hal-03033777
[AC22]: https://hal.archives-ouvertes.fr/hal-03479582/
[Levy22]: https://hal.science/hal-03694177
[LTH22]: https://inria.hal.science/hal-03548226
[Swarm22]: https://hal.science/hal-04502507
[CAID23]: https://hal.science/hal-04328529
[HID23]: https://hal.science/hal-03157141
[RSS23]: https://hal.science/hal-03654720
[SLTH23]: https://hal.science/hal-04143024
[Hyper24]: https://hal.science/hal-04389639
[JIE24]: https://onlinelibrary.wiley.com/doi/10.1111/jiec.13582
[JOSS24]: https://joss.theoj.org/papers/10.21105/joss.05772
[SCHED24]: https://hal.science/hal-04497548
[SSLT24]: https://hal.science/hal-04741369
[FedLSF25]: https://hal.science/hal-05094752
[GENE25]: https://hal.science/hal-05078291
[ShapFMRI25]: https://hal.science/hal-04596845
[BRAVA26]: https://hal.science/hal-05502800
[RAES26]: https://doi.org/10.4230/LIPIcs.STACS.2026.6
[NeuronPrune26]: https://hal.science/hal-05507068
[QuantPrune26]: https://hal.science/hal-05251970
[TSPPosEnc26]: https://hal.science/hal-05295614
[NoisyPull26]: https://hal.science/hal-04778388
[OrderStats26]: https://hal.science/hal-05548829
[Levy3D26]: https://hal.science/hal-05551262
[DejaVu26]: https://hal.science/hal-05585653
