---
title: "A Bayesian Approach to Informed Spatial Filtering with Robustness Against DOA Estimation Errors"
collection: publications
permalink: /publication/2017-10-IEEE-TASLP-BSFMW
excerpt: ''
date: 2017-10-01
venue: 'IEEE/ACM Transactions on Audio, Speech, and Language Processing, to appear'
---

[Download the Paper here](http://Soumitro-Chakrabarty.github.io/files/17_TASLP_paper.pdf)

A Bayesian approach to spatial filtering is presented, which
is robust to uncertain or erroneous direction-of-arrival (DOA) information.
The proposed framework aims to capture multiple sound sources at
each time-frequency (TF) instant with an arbitrary direction dependent
gain, while attenuating the diffuse sound and noise. For robustness, the
DOA corresponding to each sound source is assumed to be a discrete
random variable with a prior defined on a discrete set of candidate
DOAs over the whole DOA space. With this assumption, the solution is
given as a weighted sum of individual spatial filters, each corresponding
to a specific combination of probable DOA values, with the weighting
factors given by the joint posterior probabilities of the combination of
DOA values. Assuming the whole DOA space as the support for each
random variable results in redundant computations and contributes to a
high computational cost. To alleviate this problem, a narrowband DOA
estimate-based posterior probability approximation method is proposed,
which isolates regions in the DOA space with high probability of
containing the actual source DOAs to compute time adaptive supports for
each random variable. Through experimental analysis, we demonstrate
the robustness of the proposed framework against DOA estimation errors.
Experimental evaluation with simulated and measured room impulse
responses, in terms of objective performance measures, demonstrates the
effectiveness of the framework to perform spatial filtering in noisy and
reverberant acoustic environments.

Authors: **S. Chakrabarty** and Emanuël Habets
