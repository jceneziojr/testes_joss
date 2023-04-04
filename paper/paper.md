---
title: 'Gala: A Python package for galactic dynamics'
tags:
  - Python
  - astronomy
  - dynamics
  - galactic dynamics
  - milky way
authors:
  - name: Adrian M. Price-Whelan
    orcid: 0000-0000-0000-0000
    equal-contrib: true
    affiliation: "1, 2" # (Multiple affiliations must be quoted)
  - name: Author Without ORCID
    equal-contrib: true # (This is how you can denote equal contributions between multiple authors)
    affiliation: 2
  - name: Author with no affiliation
    corresponding: true # (This is how to denote the corresponding author)
    affiliation: 3
affiliations:
 - name: Lyman Spitzer, Jr. Fellow, Princeton University, USA
   index: 1
 - name: Institution Name, Country
   index: 2
 - name: Independent Researcher, Country
   index: 3
date: 13 August 2017
bibliography: paper.bib

# Optional fields if submitting to a AAS journal too, see this blog post:
# https://blog.joss.theoj.org/2018/12/a-new-collaboration-with-aas-publishing
aas-doi: 10.3847/xxxxx <- update this with the DOI from AAS once you know it.
aas-journal: Astrophysical Journal <- The name of the AAS journal.
---

# Summary

The field of System Identification (SI) aims to build mathematical models for static and dynamic behavior from experimental data [@Lju1987]. In particular, nonlinear system identification has become a central issue in the SI community, and from the 1950s onwards many methods have been proposed. In this respect, NARMAX (Nonlinear AutoRegressive Moving Average with eXogenous input) models are among the most well-documented and used model representation of dynamical systems [@Bil2013].

In this context, `SysIdentPy` is a package designed for system identification using polynomial NARMAX models [@Wil2020]. It can handle SISO (Single-Input Single-Output) and MISO (Multiple-Inputs Single-Output) NARMAX model identification and its variants such as NARX, NAR, ARMAX, ARX, and AR models. `SysIdentPy` provides various tools for both model structure selection and parameter estimation including classical algorithms, e.g., forward regression orthogonal least squares and extended least squares orthogonal forward regression; parameter estimation using ordinary least squares, recursive algorithms and adaptative filters; the Akaike Information Criterion (AIC), Bayesian Information Criterion (BIC), Khinchin's law of iterated logarithm criterion (LILC), and Final Prediction Error (FPE) methods for model order selection [@HK1999]; regression metrics; and residual analysis. The reader is referred to the package documentation for further details.


