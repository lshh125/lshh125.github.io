---
layout: archive
title: "Research"
permalink: /proj/
author_profile: true
redirect_from:
  - /proj
---

My research develops machine-learning methods that connect molecular measurements, tissue context, and cellular responses. I focus on representations that preserve meaningful biological variation, generative prediction of cells and tissues, and explanations that help identify testable molecular programs and cellular relationships.
{: .research-overview }

## Generative and Interpretable Models of Tissue Biology

Model cellular states within their tissue environment through interpretable cell interactions and generative prediction.

**Ongoing work:** In collaboration with Xin Jin, I analyze mouse-brain spatial perturbation data to study cell-autonomous and neighboring-cell responses.

### TissueNarrator (2025)

TissueNarrator uses generative language modeling of molecular profiles and spatial context to generate cellular profiles and predict cellular responses.

**Preprint:** *TissueNarrator: Generative Modeling of Spatial Transcriptomics with Large Language Models.* bioRxiv (2025).<br>
[Paper](https://www.biorxiv.org/content/10.1101/2025.11.24.690325v1) · [Code](https://github.com/ma-compbio-lab/TissueNarrator)

### STEAMBOAT (2025)

STEAMBOAT uses self-supervised attention to distinguish intrinsic cellular programs from local and long-range tissue context.

**Publication:** *STEAMBOAT: Attention-based multiscale delineation of cellular interactions in tissues.* RECOMB (2025).<br>
Extended manuscript accepted in principle by *Nature Methods*.<br>
[Conference paper](https://doi.org/10.1007/978-3-031-90252-9_55) · [Preprint](https://www.biorxiv.org/content/10.1101/2025.04.06.647437v1) · [Code](https://github.com/ma-compbio/Steamboat) · [Docs](https://steamboat.readthedocs.io/en/latest/)

## Single-Cell Representation Learning and Integration

Develop representations that preserve biological structure, identify informative features, and integrate measurements across modalities and samples.

### SCMER (2021)

SCMER selects compact molecular feature panels that preserve cell-state organization and rare populations across single-cell assays.

**Publication:** *Single-cell manifold-preserving feature selection for detecting rare cell populations.* Nature Computational Science (2021).<br>
[Paper](https://doi.org/10.1038/s43588-021-00070-7) · [Code](https://github.com/KChen-lab/scmer) · [Docs](https://scmer.readthedocs.io/en/latest/examples.html)

### Cyclum (2020)

Cyclum infers latent periodic processes, such as cell-cycle progression, from single-cell expression data using a circular representation.

**Publication:** *Latent periodic process inference from single-cell RNA-seq data.* Nature Communications (2020).<br>
[Paper](https://www.nature.com/articles/s41467-020-15295-9) · [Code](https://github.com/KChen-lab/cyclum)

### bindSC (2022)

bindSC integrates measurements across single-cell modalities using bi-order canonical correlation analysis.

**Publication:** *Bi-order multimodal integration of single-cell data.* Genome Biology (2022).<br>
[Paper](https://link.springer.com/article/10.1186/s13059-022-02679-x) · [Code](https://github.com/KChen-lab/bindSC)

### LAD (2024)

LAD uses label-aware distance to reduce temporal and spatial variability in clustering and visualization of single-cell data.

**Publication:** *Label-aware distance mitigates temporal and spatial variability for clustering and visualization of single-cell gene expression data.* Communications Biology (2024).<br>
[Paper](https://www.nature.com/articles/s42003-024-05988-y) · [Code](https://github.com/KChen-lab/lad)

## Statistical Inference and Experimental Design

Support reliable conclusions and efficient experiments through methods for batch-aware testing, effect-size estimation, and sample-size planning.

### Sensei (2022)

Sensei estimates sample sizes needed to detect changes in cell-type abundance.

**Publication:** *Sensei: how many samples to tell a change in cell type abundance?* BMC Bioinformatics (2022).<br>
[Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04526-5) · [Web app](https://kchen-lab.github.io/sensei/table_beta.html)

### Stratified tests and weighted common-language effect size (2021)

Stratified tests identify differential gene expression under batch effects, with a weighted common-language effect size for the van Elteren test.

**Publication:** *Stratified Test Accurately Identifies Differentially Expressed Genes Under Batch Effects in Single-Cell Data.* IEEE/ACM Transactions on Computational Biology and Bioinformatics (2021).<br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9476999) · [Code](https://github.com/KChen-lab/stratified-tests-for-seurat)

## Perturbation Biology and Immune Responses

Connect genetic perturbations, antigen presentation, and immune-cell states with immune function and responses to intervention.

### Single-cell CRISPR immune screens (2022)

This study combines Perturb-seq, CROP-seq, and immune assays to examine how tumor-intrinsic genes shape responses to T-cell killing and anti-PD-1 therapy.

**Publication:** *Single-cell CRISPR immune screens reveal immunological roles of tumor intrinsic factors.* NAR Cancer (2022).<br>
[Paper](https://academic.oup.com/narcancer/article/4/4/zcac038/6884717)

### EpiNB

EpiNB predicts MHC-I antigen presentation through a software package and web application.

[Code](https://github.com/KChen-lab/epiNB) · [Web app](https://epinbweb.streamlit.app/)

### SARS-CoV-2–specific T-cell differentiation (2022)

This study characterizes the differentiation states and functional diversity of SARS-CoV-2–specific T cells in vaccinated individuals.

**Publication:** *In-depth analysis of SARS-CoV-2–specific T cells reveals diverse differentiation hierarchies in vaccinated individuals.* JCI Insight (2022).<br>
[Paper](https://insight.jci.org/articles/view/156559)

### CAR-NK therapy resistance (2023)

This collaborative study investigates metabolic changes associated with resistance to CAR-NK cell therapy and evaluates cytokine engineering to improve tumor control.

**Publication:** *Loss of metabolic fitness drives tumor resistance after CAR-NK cell therapy and can be overcome by cytokine engineering.* Science Advances (2023).<br>
[Paper](https://doi.org/10.1126/sciadv.add6997)

### Regulatory T cells and immunotherapy response (2025)

This collaborative study examines the association between depletion of effector regulatory T cells and major response to induction dual immune checkpoint blockade.

**Publication:** *Depletion of effector regulatory T cells associates with major response to induction dual immune checkpoint blockade.* Cancer Discovery (2025).<br>
[Paper](https://doi.org/10.1158/2159-8290.CD-24-1390)
