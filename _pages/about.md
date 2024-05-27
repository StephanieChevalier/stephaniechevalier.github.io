---
layout: archive
permalink: /
title: "Stéphanie Chevalier"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am currently a bioinformatics postdoctoral fellow in translational medicine at Servier,
<span class=important>working on a systems biology approach to prioritize drug combination strategies</span>.
My research is involved in the challenging issue of modeling biological systems and predicting behaviors under perturbations to support therapeutic solution research, via **biological knowledge graphs and dynamical models of biological regulations**.

I am highly motivated by the translation of fundamental research into health care advances, with a particular interest in multisystemic disorders.
<!-- I have a special affinity for the holistic approach of systems biology to explore biological phenomena.-->
During my training, I could successively approach complementary bioinformatics perspectives: the challenge of data integration, NGS analysis, structural analysis for drug design, and finally, the one of complex biological systems analysis and modelling.

<hr class="hr_gradient" />

## PhD topic

**PhD in computer science for a systems biology issue:** <important>modelling of regulatory mechanisms</important>.

I contributed to <important>a method for automatic inference of discrete dynamical models of biological interactions</important> governing complex cell behaviors, called <important>BoNesis</important>.
It allows to **model regulatory mechanisms of biological processes with complex dynamic properties**, such as cell differentiation, by taking into account **knowledge on thousands of genes**.

[![BoNesis-principle](../images/bonesis_principle.png){:class="img-page"}](https://github.com/bnediction/bonesis)

This modeling confronts **prior knowledge** on interactions with **observations** along the process to model (bulk/single cell gene expressions, perturbations, mutations...). It can then <important>enumerate all Boolean networks reproducing a complex behavior</important> (under _[mp semantics](https://hal.archives-ouvertes.fr/hal-01864693v2/document)_), e.g. cell differentiation. It can also be used to help <important>select relevant nodes among a large prior knowledge network</important> (e.g. from public interaction databases).

Method based on Answer-Set-Programming.
