---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A rapid refresh ensemble based data assimilation and forecast system for the
  RELAMPAGO field campaign
subtitle: ''
summary: ''
authors:
- María Eugenia Dillon
- Paula Maldonado
- Paola Corrales
- Yanina García Skabar
- Juan Ruiz
- Maximiliano Sacco
- Federico Cutraro
- Leonardo Mingari
- Cynthia Matsudo
- Luciano Vidal
- Martin Rugna
- María Paula Hobouchian
- Paola Salio
- Stephen Nesbitt
- Celeste Saulo
- Eugenia Kalnay
- Takemasa Miyoshi
tags:
- Regional data assimilation
- Regional ensemble forecasts
- RELAMPAGO
categories: []
date: '2021-01-01'
lastmod: 2022-02-19T15:10:13-06:00
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
publishDate: '2022-02-19T21:10:12.800668Z'
publication_types:
- '2'
abstract: This paper describes the lessons learned from the implementation of a regional
  ensemble data assimilation and forecast system during the intensive observing period
  of the Remote sensing of Electrification, Lightning, And Mesoscale/microscale Processes
  with Adaptive Ground Observations (RELAMPAGO) field campaign (central Argentina,
  November–December 2018). This system is based on the coupling of the Weather Research
  and Forecasting (WRF) model and the Local Ensemble Transform Kalman Filter (LETKF).
  It combines multiple data sources both global and locally available like high-resolution
  surface networks, AMDAR data from local aircraft flights, soundings, AIRS retrievals,
  high-resolution GOES-16 wind estimates, and local radar data. Hourly analyses with
  grid spacing of 10 km are generated along with warm-start 36-h ensemble-forecasts,
  which are initialized from the rapid refresh analyses every three hours. A preliminary
  evaluation shows that a forecast error reduction is achieved due to the assimilated
  observations. However, cold-start forecasts initialized from the Global Forecasting
  System Analysis slightly outperform the ones initialized from the regional assimilation
  system discussed in this paper. The system uses a multi-physics approach, focused
  on the use of different cumulus and planetary boundary layer schemes allowing us
  to conduct an evaluation of different model configurations over central Argentina.
  We found that the best combinations for forecasting surface variables differ from
  the best ones for forecasting precipitation, and that differences among the schemes
  tend to dominate the forecast ensemble spread for variables like precipitation.
  Lessons learned from this experimental system are part of the legacy of the RELAMPAGO
  field campaign for the development of advanced operational data assimilation systems
  in South America.
publication: '*Atmospheric Research*'
doi: https://doi.org/10.1016/j.atmosres.2021.105858
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0169809521004142
---
