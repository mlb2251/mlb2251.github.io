---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
classes: wide

---

I'm a PhD student at MIT co-advised by [Armando Solar-Lezama](https://people.csail.mit.edu/asolar/) in EECS and [Josh Tenenbaum](http://cocosci.mit.edu/josh) in BCS. My research combines methods from programming languages (PL) research with machine learning to tackle problems in artificial intelligence.

New draft of my latest work, *Pluck*, accepted to PLDI 2025: [*Stochastic Lazy Knowledge Compilation for Inference in Discrete Probabilistic Programs*](pluck_pldi2025.pdf); the [code artifact](https://github.com/mlb2251/pluck-artifact) is still being reviewed, but we will polish and fully release a Pluck library and tutorial in the next few weeks ([tutorial preview](https://github.com/mlb2251/PluckArtifactDependency.jl/blob/9df334af11a53a9dc51d7fe6b78b63d3331994a8/USAGE.md)).

<!-- Also check out my work Stitch, published in POPL 2023: [*Top-Down Synthesis for Library Learning*](https://dl.acm.org/doi/10.1145/3571234); with [code](https://github.com/mlb2251/stitch) along with [tutorial & docs](https://stitch-bindings.readthedocs.io/en/stable/). -->

# Research Interests

My research interests center on program synthesis, probabilistic programming, and artificial intelligence. I’m particularly interested in [neurosymbolic methods](http://www.neurosymbolic.org/methods.html) that bridge the machine learning and programming languages communities. I believe symbolic methods can augment neural methods to facilitate low-data learning, generalization, transfer learning, interpretability, and other desiderata.

I'm particularly interested in abstraction learning, as in Ellis et al.'s [DreamCoder](https://arxiv.org/abs/2006.08381). I led follow up work building a tool called Stitch ([paper](https://dl.acm.org/doi/10.1145/3571234) & [code](https://github.com/mlb2251/stitch)) published at POPL 2023 that achieves a 1,000-10,000x speedup in abstraction learning over DreamCoder. I'm interested in exploring new applications of abstraction learning, and I'm particularly interested in its application to world modelling through probablistic programs.

I previously published as Matthew Bowers.

[Google Scholar](https://scholar.google.com/citations?user=ghdbIsoAAAAJ) / [CV](CV.pdf) / [Github](https://github.com/mlb2251) / [Bluesky](https://bsky.app/profile/mlbowers.bsky.social) / [Twitter](https://twitter.com/mattlbowers) / [Email](mailto:mlbowers@csail.mit.edu) (mlbowers@csail.mit.edu)

<!-- Prior to Stitch I worked with Max Nye on [Representing Partial Programs with Blended Abstract Semantics](https://arxiv.org/pdf/2012.12964) at ICLR 2021, and I continue to be interested of new ways of representing programs and guiding search. Search mechanisms that use learned symbolic components are particularlly interesting to me, like the predicate learning of Odena et al. in [BUSTLE: Bottom-Up Program Synthesis Through Learning-Guided Exploration](https://arxiv.org/abs/2007.14381) and [Learning to Represent Programs with Property Signatures](https://arxiv.org/abs/2002.09030). -->

<!-- I worked in chemistry in the past and am also interested in applications of neurosymbolic program synthesis to developing interpretable scientific models, as in our [NSF Expeditions](http://www.neurosymbolic.org/) project. -->


# Conference Publications

- [**Stochastic Lazy Knowledge Compilation for Inference in Discrete Probabilistic Programs**](pluck_pldi2025.pdf) (*PLDI 2025*; preprint coming soon).<br><u>Maddy Bowers*</u>, Alexander K. Lew*, Joshua B. Tenenbaum, Armando Solar-Lezama, Vikash Mansinghka.
- [**LILO: Learning Interpretable Libraries by Compressing and Documenting Code**](https://arxiv.org/abs/2310.19791) (*ICLR 2024*).<br>Gabriel Grand, Lionel Wong, <u>Maddy Bowers</u>, Theo X. Olausson, Muxin Liu, Joshua B. Tenenbaum, Jacob Andreas.
- [**Language Models Can Teach Themselves to Program Better**](https://arxiv.org/abs/2207.14502) (*ICLR 2023*).<br>Patrick Haluptzok, <u>Maddy Bowers</u>, Adam Tauman Kalai.
- [**Top-Down Synthesis for Library Learning**](https://dl.acm.org/doi/10.1145/3571234) (*POPL 2023*; *William A. Martin Master’s Thesis Award (2024)*; *Awarded Artifact Reusable*; [**code**](https://github.com/mlb2251/stitch); [**tutorial & docs**](https://stitch-bindings.readthedocs.io/en/stable/)).<br><u>Maddy Bowers</u>, Theo X. Olausson, Lionel Wong, Gabriel Grand, Joshua B. Tenenbaum, Kevin Ellis, Armando Solar-Lezama.
- [**Representing Partial Programs With Blended Abstract Semantics**](https://arxiv.org/abs/2012.12964) (*ICLR 2021*).<br>Maxwell Nye, Yewen Pu, <u>Maddy Bowers</u>,  Jacob Andreas, Joshua B. Tenenbaum, Armando Solar-Lezama. 
- [**Universal Reshaping of Arrested Colloidal Gels via Active Doping**](https://doi.org/10.1063/5.0016514) (*The Journal of Chemical Physics 2020*).<br>Stewart Mallory, <u>Maddy Bowers</u>, Angelo Cacciuto.
- [**Active Sculpting of Colloidal Crystals**](https://doi.org/10.1063/1.5082949) (*The Journal of Chemical Physics 2019*).<br>Shibananda Das, <u>Maddy Bowers</u>, Clara Bakker, Angelo Cacciuto.

# Workshop Publications

- **Lazy Knowledge Compilation for Discrete PPLs** (*Languages For Inference Workshop at POPL 2025*).<br><u>Maddy Bowers*</u>, Alexander K. Lew*, Joshua B. Tenenbaum, Vikash Mansinghka, Armando Solar-Lezama.
- **MathDSL: A Domain-Specific Language for Concise Mathematical Solutions Via Program Synthesis** (*Math-AI workshop at NeurIPS 2025*).<br>Sagnik Anupam, <u>Maddy Bowers</u>, Omar Costilla-Reyes, Armando Solar-Lezama.
- **Concept Learning as Coarse-to-Fine Probabilistic Program Induction** (*Poster (Abstract) at CogSci 2024*; [poster](poster_ctf.pdf)).<br><u>Maddy Bowers*</u>, Alexander K. Lew*, Wenhao Qi, Vikash Mansinghka, Joshua Rule, Joshua B. Tenenbaum, Armando Solar-Lezama.
- **Toward Probabilistic Coarse-to-Fine Program Synthesis** (*Languages for Inference Workshop at POPL 2024*).<br><u>Maddy Bowers*</u>, Alexander K. Lew*, Vikash Mansinghka, Joshua B. Tenenbaum, Armando Solar-Lezama.
- **Codeplay: Autotelic Learning through Collaborative Self-Play in Programming Environments** (*Intrinsically Motivated Open-ended Learning Workshop at NeurIPS 2024*).<br> Laetitia Teodorescu, Cédric Colas, <u>Maddy Bowers*</u>, Thomas Carta, Pierre-Yves Oudeyer.

# Awards

- William A. Martin Master’s Thesis Award (2024) ([Master's Thesis](https://dspace.mit.edu/handle/1721.1/151374))
- NSF Graduate Research Fellowship (2022)

See my [CV](CV.pdf) for earlier awards



<!-- # Background
In 2020 I graduated from Columbia University with a BA in Computer Science and a BA in Chemistry. At Columbia, I worked with Professor Angelo Cacciuto on chemical simulations of self-assembling colloids and authored two publications:
- Das, S., Lee Bowers, M., Bakker, C., & Cacciuto, A. (2019). Active sculpting of colloidal crystals. *The Journal of Chemical Physics*, 150 (13), 134505.
- Mallory, S., Lee Bowers, M., & Cacciuto, A. (2020). Universal reshaping of arrested colloidal gels via active doping. *The Journal of Chemical Physics*, 153, 084901.

In the summer of 2019, I worked in the [Learning Matter Group](http://gomezbombarelli.mit.edu/) at MIT under Professor Rafael Gomez-Bombarelli, where I applied graph neural network methods to molecular property prediction. I'm interested in combining these methods with program synthesis techniques in a chemical domain in the future. -->

<!-- # Fun Stuff-->

<!--I wrote [Coral](https://github.com/jacobaustin123/Coral), a gradually-typed Python compiler which runs type inference and generates fast equivalent LLVM-IR code whenever possible.-->

<!--I wrote [Espresso](https://github.com/mlb2251/espresso), a Bash-Python hybrid shell that I used for several years, though I've recently migrated to [Xonsh](https://xon.sh/).-->

<!--I like writing my own tools and libraries to speed up development, some of which I've packaged into the [mlb](https://github.com/mlb2251/mlb) Python library.-->

