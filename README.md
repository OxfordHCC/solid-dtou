Perennial DToU, on SoLiD
======

This repo is a meta-repo for the work about Perennial Semantic Data Terms of Use (DToU, or psDToU), originally reported in [our WWW 2024 paper](https://doi.org/10.1145/3589334.3645631).

> The work is being continuously improved. [See here](https://github.com/OxfordHCC/solid-dtou) if you want to see the repo for the WWW 2024 paper.

Try from [this repo's Pages](https://renyuneyun.github.io/solid-dtou/) if you encounter any unexpected rendering of resources (e.g. DToU Spec).

## Introductory Resources

If you want to understand what is DToU, and how it differs from other approaches (e.g. ODRL), the following would be of interest to you.

### Overview

- [3-min Video Intro](https://www.youtube.com/watch?v=ERFZdnOq09Y)
- [Poster](./Poster-WWW2024.pdf)

### In-practice or in-details
  
- [Demo apps for DToU + Solid](https://github.com/renyuneyun/dtou-demo-sosy): Demo apps for [SoSy2026](https://sosy26.eu) Authz Session
	- You need a compatible Solid service -- see below
- [DToU Spec](./dtou-spec.html): specification of the DToU policy language
- Paper: [DOI 10.1145/3589334.3645631](https://doi.org/10.1145/3589334.3645631)
  - arxiv: [2403.07587](https://arxiv.org/abs/2403.07587)

## Repo and Code

If you want to try it in practice, host your service, or dig into details, see below.

- [DToU lang](https://github.com/renyuneyun/dtou-lang): The repo for the DToU language, containing the reasoner (the core of the DToU policy engine), mainly N3 rules, and the basic rules for the language (and example rules)
- [CSS with DToU](https://github.com/renyuneyun/CommunitySolidServer): The repo for the modified CSS (Community Solid Server) where the DToU engine is integrated with
  - The DToU engine uses the same reasoner (N3 rules) as the DToU reasoner repo above
- [DToU Demo App](https://github.com/renyuneyun/dtou-demo-app): The repo for the demo App for demonstrating the integration
  - It also contains the benchmark scripts

## Citation Guideline

If you want to cite this work, please cite the WWW 2024 paper like the following:

> R. Zhao and J. Zhao, ‘Perennial Semantic Data Terms of Use for Decentralized Web’, in Proceedings of The ACM Web Conference 2024, Singapore: ACM, May 2024, pp. 2238–2249. doi: 10.1145/3589334.3645631.

or, if you use LaTeX:

```latex
@inproceedings{zhao_perennial_2024,
  title = {Perennial {{Semantic Data Terms}} of {{Use}} for {{Decentralized Web}}},
  booktitle = {Proceedings of {{The ACM Web Conference}} 2024},
  author = {Zhao, Rui and Zhao, Jun},
  year = 2024,
  month = may,
  pages = {2238--2249},
  publisher = {ACM},
  address = {Singapore},
  doi = {10.1145/3589334.3645631}
}

```

## Interested in More?

The work is conducted as a part of the [EWADA Project](https://ewada.ox.ac.uk/) at [Human-Centred Computing Group](https://hcc.cs.ox.ac.uk/), Department of Computer Science, University of Oxford. Find out more about EWADA's work, or [my other work](https://me.ryey.icu) :)

