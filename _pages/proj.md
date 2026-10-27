---
layout: archive
title: "Research"
permalink: /proj/
author_profile: true
redirect_from:
  - /proj
---

## Current Focus - Generative and Interpretable Models of Tissue Biology

Model cellular states within their tissue environment through interpretable cell interactions and generative prediction.

<figure class="research-figure">
  <img src="{{ '/images/website-figure.png' | relative_url }}" alt="Research overview: spatial neighbors, molecular profiles, tissue context, perturbation biology, and prior knowledge inform AI and language models to predict cellular responses and identify candidate perturbations, extract testable biological hypotheses, and support future virtual tissues, AI agents, and lab feedback loops.">
</figure>

**Ongoing work:** In collaboration with Xin Jin, I analyze mouse-brain spatial perturbation data to study cell-autonomous and neighboring-cell responses.

**TissueNarrator** — Uses generative language modeling of molecular profiles and spatial context to generate cellular profiles and predict cellular responses. [Preprint](https://www.biorxiv.org/content/10.1101/2025.11.24.690325v1) · [Code](https://github.com/ma-compbio-lab/TissueNarrator)

**STEAMBOAT** — Uses self-supervised attention to distinguish intrinsic cellular programs from local and long-range tissue context. [Paper (RECOMB)](https://doi.org/10.1007/978-3-031-90252-9_55) · [Preprint](https://www.biorxiv.org/content/10.1101/2025.04.06.647437v1) (extended manuscript accepted in principle by *Nature Methods*) · [Code](https://github.com/ma-compbio/Steamboat) · [Docs](https://steamboat.readthedocs.io/en/latest/)

## Single-Cell Representation Learning and Integration

Develop representations that preserve biological structure, identify informative features, and integrate measurements across modalities and samples.

**SCMER** — Selects compact molecular feature panels that preserve cell-state organization and rare populations across single-cell assays. [Paper (Nature Computational Science)](https://doi.org/10.1038/s43588-021-00070-7) · [Code](https://github.com/KChen-lab/scmer) · [Docs](https://scmer.readthedocs.io/en/latest/examples.html)

**Cyclum** — Infers latent periodic processes, such as cell-cycle progression, from single-cell expression data using a circular representation. [Paper (Nature Communications)](https://www.nature.com/articles/s41467-020-15295-9) · [Code](https://github.com/KChen-lab/cyclum)

**bindSC** — Integrates measurements across single-cell modalities using bi-order canonical correlation analysis. [Paper (Genome Biology)](https://link.springer.com/article/10.1186/s13059-022-02679-x) · [Code](https://github.com/KChen-lab/bindSC)

**LAD** — Uses label-aware distance to reduce temporal and spatial variability in clustering and visualization of single-cell data. [Paper (Communications Biology)](https://www.nature.com/articles/s42003-024-05988-y) · [Code](https://github.com/KChen-lab/lad)

## Statistical Inference and Experimental Design

Support reliable conclusions and efficient experiments through methods for batch-aware testing, effect-size estimation, and sample-size planning.

**Sensei** — Estimates sample sizes needed to detect changes in cell-type abundance. [Paper (BMC Bioinformatics)](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04526-5) · [Web app](https://kchen-lab.github.io/sensei/table_beta.html)

**Stratified tests and weighted common-language effect size** — Methods for differential-expression analysis under batch effects, including a weighted common-language effect size for the van Elteren test. [Paper (IEEE/ACM TCBB)](https://ieeexplore.ieee.org/abstract/document/9476999) · [Code](https://github.com/KChen-lab/stratified-tests-for-seurat)

## Perturbation Biology and Immune Responses

Connect genetic perturbations, antigen presentation, and immune-cell states with immune function and responses to intervention.

**Single-cell CRISPR immune screens** — Combines Perturb-seq, CROP-seq, and immune assays to examine how tumor-intrinsic genes shape responses to T-cell killing and anti-PD-1 therapy. [Paper (NAR Cancer)](https://academic.oup.com/narcancer/article/4/4/zcac038/6884717)

**EpiNB** — Predicts MHC-I antigen presentation through a software package and web application. [Code](https://github.com/KChen-lab/epiNB) · [Web app](https://epinbweb.streamlit.app/)

**SARS-CoV-2–specific T-cell differentiation** — Characterizes the differentiation states and functional diversity of SARS-CoV-2–specific T cells in vaccinated individuals. [Paper (JCI Insight)](https://insight.jci.org/articles/view/156559)

**CAR-NK therapy resistance** — A collaborative study that investigates metabolic changes associated with resistance to CAR-NK cell therapy and evaluates cytokine engineering to improve tumor control. [Paper (Science Advances)](https://doi.org/10.1126/sciadv.add6997)

**Regulatory T cells and immunotherapy response** — A collaborative study that examines the association between depletion of effector regulatory T cells and major response to induction dual immune checkpoint blockade. [Paper (Cancer Discovery)](https://doi.org/10.1158/2159-8290.CD-24-1390)
