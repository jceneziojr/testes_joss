---
title: 'SysIdentPyGUI: A Graphical User Interface for System Identification using NARMAX models'
tags:
  - GUI
  - Graphical User Interface
  - Python
  - System Identification
  - NARMAX
  - Dynamical Systems
  - Model Structure Selection
authors:
  - name: Júlio César Enezio Júnior
    orcid: 0009-0005-8510-3432
    affiliation: "1" 
  - name: Wilson Rocha Lacerda Junior
    affiliation: "1" 
  - name: Samir Angelo Milani Martins
    affiliation: "1, 2"
affiliations:
 - name: GCoM - Modeling and Control Group at Federal University of São João del-Rei, Brazil
   index: 1
 - name: Department of Electrical Engineering at Federal University of São João del-Rei, Brazil
   index: 2
date: 03 April 2023
bibliography: paper.bib
---

# Summary

The field of System Identification (SI) aims to build mathematical models for static and dynamic behavior from experimental data [@Lju1987]. In particular, nonlinear system identification has become a central issue in the SI community, and from the 1950s onwards many methods have been proposed. In this respect, NARMAX (Nonlinear AutoRegressive Moving Average with eXogenous input) models are among the most well-documented and used model representation of dynamical systems [@Bil2013].

In this context, `SysIdentPy` is a package designed for system identification using polynomial NARMAX models [@Wil2020]. It can handle SISO (Single-Input Single-Output) and MISO (Multiple-Inputs Single-Output) NARMAX model identification and its variants such as NARX, NAR, ARMAX, ARX, and AR models. `SysIdentPy` provides various tools for both model structure selection and parameter estimation including classical algorithms, e.g., forward regression orthogonal least squares and extended least squares orthogonal forward regression; parameter estimation using ordinary least squares, recursive algorithms and adaptative filters; the Akaike Information Criterion (AIC), Bayesian Information Criterion (BIC), Khinchin's law of iterated logarithm criterion (LILC), and Final Prediction Error (FPE) methods for model order selection [@HK1999]; regression metrics; and residual analysis. The reader is referred to the package documentation for further details.

# Statement of need - SysIdentPyGUI

`SysIdentPyGUI` is a web app for the Python module `SysIdentPy` in the format of a Graphical User Interface (GUI). It was written using the `Streamlit` library, which allows the creation of web apps in a compact Python syntax. `SysIdentPyGUI` comes as an use alternative for people that would like to use `SysIdentPy` toolbox but aren't familiar with Python, such as medical or economy students. 



# References

