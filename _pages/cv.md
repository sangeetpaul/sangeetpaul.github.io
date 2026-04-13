---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Physics, University of Oregon, 2025
* BSc-MSc in Physics, NISER, HBNI, 2018

Skills
======
* __General__: Bayesian statistics, MCMC, Cluster analysis, Digital signal processing, Machine learning, Normalizing flows
* __Machine learning__: tensorflow, keras, scikit-learn
* __GPU acceleration__: jax, cupy, CUDA
* __Miscellaneous__: emcee, pandas, scipy, numpy, matplotlib, numpyro
* __Programming Languages__: _fluent in_ Python; _working knowledge of_ C, C++, R, Java
* __Software__: VS Code, Jupyter, PyCharm, Git, LaTeX, Mathematica, MATLAB
* __Astronomy__: astropy, bilby, pycbc, gwpy
* __Physics__: Gravitational-wave astronomy, General relativity, Quantum mechanics, Quantum field theory
* __Natural Languages__: English, Hindi, Odia, Bengali, Gahaḷā

Work experience
======
* 2019-2025: __Research Assistant__ at Institute of Fundamental Sciences, University of Oregon
  * Supervisor: Ben Farr
  * __Hierarchical mergers of binary black holes in dynamical astrophysical environments__: Built JAX-accelerated Bayesian population inference software to find evidence of hierarchical mergers of binary black holes in gravitational wave catalogs using the coagulation model for black hole mergers in dynamical astrophysical environments, such as globular clusters and active galactic nuclei’ accretion disks.
  * __Joint inference of astrophysical and noise parameters in gravitational wave data__: Built high-dimensional Bayesian inference software for time-series and frequency-series data from gravitational-wave interferometers to estimate astrophysical signal models and spline-based detector noise models simultaneously. Found localized correlations between signal waveform and noise power spectral density.
  * __Clustering algorithms for significantly uncertain data__: Built algorithms to cluster data with high uncertainty, such as data from gravitational-wave interferometers. Found probabilistic clusters and outliers in mass–spin space.

* 2019-2025: __Teaching Assistant__ at Department of Physics, University of Oregon
  * __Graduate-level__: Scientific computation (machine learning), Design of experiments (Bayesian statistics).
  * __Undergrad-level__: Quantum mechanics, Astrophysics, Astronomy, Fourier analysis, Algebra-based physics, Calculus-based physics.

* 2018-2019: __Research Fellow__ at NISER, HBNI
  * __Blackfolds in higher-dimensional gravity__: Analyzed the stability of higher-dimensional equivalents of black holes. Verified through simulations that a perturbed black string asymptotically settles down to a black hole due to the Gregory–Laflamme instability.

* 2013-2018: __Research Scholar__ at NISER, HBNI
  * __Membrane – gravity duality in a large number of dimensions__: Demonstrated that black hole event horizons are analogous to hydrodynamic membranes.
  * __Analytical predictions of the mass function of halos__: Analyzed the effects of varying dark matter halos’ mass functions on astronomical and cosmological observations.
  * __Magneto-optic Kerr effect__: experiment design: Constructed theory for an experiment to use the magneto-optic Kerr effect to analyze magnetized surfaces.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Vice-President, Graduate Student Council, Dept of Physics, U Oregon
* PhD Admissions Committee, Dept of Physics, U Oregon
* Graduate Support Group, Dept of Physics, U Oregon
