---
layout: research
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## PhD topic

**PhD in computer science for a systems biology issue:** <span class=important>modelling of regulatory mechanisms</span>.

I contributed to <span class=important>a method for automatic inference of discrete dynamical models of biological interactions</span> governing complex cell behaviors, called BoNesis.
It allows to **model regulatory mechanisms of biological processes with complex dynamic properties**, such as cell differentiation, by taking into account **knowledge on thousands of genes**.

[![BoNesis-principle](../images/bonesis_principle.png){:class="img-page"}](https://github.com/bnediction/bonesis)

This modeling confronts **prior knowledge** on interactions with **observations** along the process to model (bulk/single cell gene expressions, perturbations, mutations...). It can then <span class=important>enumerate all Boolean networks reproducing a complex behavior</span> (under _[mp semantics](https://hal.archives-ouvertes.fr/hal-01864693v2/document)_), e.g. cell differentiation. It can also be used to help <span class=important>select key regulatory genes among a large gene regulatory network</span> (e.g. from public interaction databases).

Method based on Answer-Set-Programming.

## Communications

<span style="font-size:smaller;">
* [Thesis](../files/manuscrit.pdf) & [defense](../files/2022-09_soutenance.pdf) --- 09/2022 --- Univ. Paris-Saclay  
**<span class=important>PhD defense</span>**
* [Presentation](../files/2021-07_WAN.pdf), international workshop --- 07/2021 --- Marseille  
**<span class=important>WAN</span>** <informative>(Workshop on Automata Networks)</informative>
* [Presentation](../files/2021-03_Bioss.pdf), national seminar --- 03/2021 --- virtual  
**<span class=important>Bioss</span>** <informative>seminar (CNRS workgroup on systemic and symbolic biology)</informative>
* [Presentation](../files/2020-12_SinCellMod.pdf), national workshop --- 12/2020 --- virtual  
**<span class=important>SinCellMod-2020</span>** <informative>(Single-Cell data in network Modeling)</informative>
* [Presentation](../files/CMSB2020.pdf), international conference --- 09/2020 --- virtual  
**<span class=important>CMSB</span>** <informative>(int. conf. on Computational Methods in Systems Biology)</informative>
* Presentation, international research school --- 03/2020 --- CIRM, Marseille  
**<span class=important>Network and molecular biology</span>**
* Presentation, local seminar --- 12/2019 --- Univ. Paris-Saclay  
**<span class=important>TheoBioR</span>** <informative>(CNRS workgroup on metabolism and hybrid methods)</informative>
* [Presentation](../files/2019-11_ICTAI.pdf), international conference --- 11/2019 --- Portland, Oregon, USA  
**<span class=important>ICTAI</span>** <informative>(Int. Conf. on Tools with Artificial Intelligence)</informative>
* Poster, international conference --- 07/2019 --- Basel, Swiss  
**<span class=important>ISMB/ECCB</span>** <informative>(European Conference on Computational Biology)</informative>
* Short presentation & poster, international course --- 09/2018 --- Institut Curie, Paris  
**<span class=important>CSBC</span>** <informative>(Computational Systems Biology of Cancer)</informative>
* Poster, local conference --- 09/2018 --- Univ. Paris-Saclay  
**<span class=important>JDSE</span>** <informative>(Junior Conference on Data Science)</informative>
* Presentation, national seminar --- 07/2018 --- Marseille  
**<span class=important>Bioss</span>** <informative>annual days (CNRS workgroup on systemic and symbolic biology)</informative>
* Poster, national conference --- 07/2018 --- Marseille  
**<span class=important>JOBIM</span>** <informative>(Journées Ouvertes en Biologie, Informatique et Mathématiques)</informative>
</span>
