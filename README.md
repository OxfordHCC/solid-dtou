Perennial DToU, on SoLiD
======

This repo is a meta-repo for the work about Perennial Data Terms of Use, particularly the paper *Perennial Semantic Data Terms of Use for Decentralized Web* accepted by International World Wide Web Conference (WWW) 2024, [DOI 10.1145/3589334.3645631](https://doi.org/10.1145/3589334.3645631).

The work is conducted as a part of the [EWADA Project](https://ewada.ox.ac.uk/) at University of Oxford.

See [the repo's pages](https://renyuneyun.github.io/solid-dtou/) for better rendering.

## Paper resources

- Paper DOI [10.1145/3589334.3645631](https://doi.org/10.1145/3589334.3645631)
  - arxiv: [2403.07587](https://arxiv.org/abs/2403.07587)

- [3-min Video Intro](https://www.youtube.com/watch?v=ERFZdnOq09Y)

- [Poster](./Poster-WWW2024.pdf)

- Code (see below)

## Sub-repos

There are several sub-repos for the code and systems mentioned in the paper:

- [DToU lang](https://github.com/renyuneyun/dtou-lang): The repo for the DToU language, containing the reasoner (the core of the DToU policy engine), mainly N3 rules, and the basic rules for the language (and example rules)
- [CSS with DToU](https://github.com/renyuneyun/CommunitySolidServer): The repo for the modified CSS (Community Solid Server) where the DToU engine is integrated with
  - The DToU engine uses the same reasoner (N3 rules) as the DToU reasoner repo above
- [DToU Demo App](https://github.com/renyuneyun/dtou-demo-app): The repo for the demo App for demonstrating the integration
  - It also contains the benchmark scripts

## Additional resources

- [DToU Spec](./dtou-spec.html): specification of the DToU policy language