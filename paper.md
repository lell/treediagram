---
title: 'TreeDiagram: Visualization for tree-based methods'
tags:
  - R
  - classification
  - random forests
  - decision trees
  - visualization
authors:
  - name: Wendy Wang
    affiliation: 1
  - name: Shufei Ge
    affiliation: "1, 2"
  - name: Shijia Wang
    affiliation: "1, 3"
  - name: Lloyd T. Elliott
    affiliation: 1
    orcid: 0000-0003-0872-7098
affiliations:
 - name: Department of Statistics and Actuarial Science, Simon Fraser University
   index: 1
 - name: Institute of Mathematical Sciences, ShanghaiTech University
   index: 2
 - name: School of Statistics and Data Science, LPMC and KLMDASR
   index: 3
date: 11 January 2021
bibliography: paper.bib

---

# Summary

Methods such as decision trees, linkage based clustering (dendrograms), binary space partitioning, and Ward's algorithm all provide hierarchical clusterings in which the data are organised at the leaves of a tree. Visualization of how the data lies within these trees is difficult (the tree can be large, unbalanced, or have internal nodes which do not linearly separate the data). In this work, we develop and implement a new method for visualizing hierarchical clusterings in which each tree split is associated with density plots and one-dimensional projections of the partitioned data. These projections are then rotated and translated within a single canvas, forming a fractal-like organisation from which the nature of the clustering can be readily appreciated. We apply this work to visualization of  four data sets involving breast cancer, ozone concentration, Higgs bosons and liver data. We can then report observations about the examined datasets including linear separability, and balance of the decision trees.

# Statement of need

`Gala` is an Astropy-affiliated Python package for galactic dynamics. Python
enables wrapping low-level languages (e.g., C) for speed without losing
flexibility or ease-of-use in the user-interface. The API for `Gala` was
designed to provide a class-based and user-friendly interface to fast (C or
Cython-optimized) implementations of common operations such as gravitational
potential and force evaluation, orbit integration, dynamical transformations,
and chaos indicators for nonlinear dynamics. `Gala` also relies heavily on and
interfaces well with the implementations of physical units and astronomical
coordinate systems in the `Astropy` package [@astropy] (`astropy.units` and
`astropy.coordinates`).

`Gala` was designed to be used by both astronomical researchers and by
students in courses on gravitational dynamics or astronomy. It has already been
used in a number of scientific publications [@Pearson:2017] and has also been
used in graduate courses on Galactic dynamics to, e.g., provide interactive
visualizations of textbook material [@Binney:2008]. The combination of speed,
design, and support for Astropy functionality in `Gala` will enable exciting
scientific explorations of forthcoming data releases from the *Gaia* mission
[@gaia] by students and experts alike.

# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$

You can also use plain \LaTeX for equations
\begin{equation}\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}
and refer to \autoref{eq:fourier} from text.

# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

If you want to cite a software repository URL (e.g. something on GitHub without a preferred
citation) then you can do it with the example BibTeX entry below for @fidgit.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

Figure sizes can be customized by adding an optional second parameter:
![Caption for example figure.](figure.png){ width=20% }

# Acknowledgements

We acknowledge contributions from Brigitta Sipocz, Syrtis Major, and Semyeong
Oh, and support from Kathryn Johnston during the genesis of this project.

# References
