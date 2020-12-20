---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Describing the shape of raindrop size distributions using uncorrelated raindrop
  mass spectrum parameters
subtitle: ''
summary: ''
authors:
- Christopher R. Williams
- V. N. Bringi
- Lawrence D. Carey
- V. Chandrasekar
- Patrick N. Gatlin
- Ziad S. Haddad
- Robert Meneghini
- S. Joseph Munchak
- Stephen Nesbitt
- Walter A. Petersen
- Simone Tanelli
- Ali Tokay
- Anna Wilson
- David B. Wolff
tags: []
categories: []
date: '2014-01-01'
lastmod: 2020-12-20T08:52:58-06:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-20T14:53:57.882287Z'
publication_types:
- '2'
abstract: Rainfall retrieval algorithms often assume a gamma-shaped raindrop size
  distribution (DSD) with three mathematical parametersNw,Dm, and μ. If only two independentmeasurements
  are available, as with the dualfrequency precipitation radar on the Global Precipitation
  Measurement (GPM) mission core satellite, then retrieval algorithms are underconstrained
  and require assumptions about DSD parameters. To reduce the number of free parameters,
  algorithms can assume that μ is either a constant or a function of Dm. Previous
  studies have suggested μ-∧ constraints [where ∧ = (4 + μ)/Dm], but controversies
  exist over whether μ-∧ constraints result from physical processes or mathematical
  artifacts due to high correlations between gamma DSDparameters. This study avoidsmathematical
  artifacts by developing joint probability distribution functions (joint PDFs) of
  statistically independent DSD attributes derived from the raindrop mass spectrum.
  These joint PDFs are thenmapped into gamma-shapedDSD parameter joint PDFs that can
  be used in probabilistic rainfall retrieval algorithms as proposed for the GPM satellite
  program. Surface disdrometer data show a high correlation coefficient between the
  mass spectrum mean diameterDm andmass spectrum standard deviation σm. To remove
  correlations betweenDSDattributes, a normalizedmass spectrumstandard deviation σ′m
  is constructed to be statistically independent of Dm, with σ′m̄ representing the
  most likely value and std(σ′m) representing its dispersion. Joint PDFs of Dm and
  μ are created from Dm and σ′m. A simple algorithm shows that rain-rate estimates
  had smaller biases when assuming the DSD breadth of σ′m̄ than when assuming a constant
  μ.
publication: '*Journal of Applied Meteorology and Climatology*'
doi: 10.1175/JAMC-D-13-076.1
---
