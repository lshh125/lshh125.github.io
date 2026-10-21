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

## TissueNarrator (2025)

TissueNarrator combines molecular profiles, metadata, spatial coordinates, and neighboring cells in a representation compatible with generative language modeling. It studies how tissue context can support the generation of cellular profiles and prediction of cellular responses.

![TissueNarrator overview](/images/tissuenarrator.png)
{: .research-figure }

**My contribution:** As senior and co-corresponding author, I helped frame the research question, design comparisons and experiments, interpret results, and write and revise the manuscript. Sizhe Liu led implementation and day-to-day analysis.

**Preprint:** *TissueNarrator: Generative Modeling of Spatial Transcriptomics with Large Language Models.* bioRxiv (2025).<br>
[Paper](https://www.biorxiv.org/content/10.1101/2025.11.24.690325v1) · [Code](https://github.com/ma-compbio-lab/TissueNarrator)

## STEAMBOAT (2025)

STEAMBOAT is a self-supervised attention framework for distinguishing intrinsic cellular programs from local and long-range tissue context. Inspectable gene programs connect its learned spatial relationships to molecular variation and support studies of how tissue context contributes to cellular responses.

![STEAMBOAT overview](/images/steamboat.png)
{: .research-figure }

**My contribution:** I conceived and led the computational development and evaluation.

**Publication:** *STEAMBOAT: Attention-based multiscale delineation of cellular interactions in tissues.* RECOMB (2025).<br>
[Conference paper](https://doi.org/10.1007/978-3-031-90252-9_55) · [Preprint](https://www.biorxiv.org/content/10.1101/2025.04.06.647437v1) · [Code](https://github.com/ma-compbio/Steamboat) · [Docs](https://steamboat.readthedocs.io/en/latest/)

## Earlier work

### LAD (2024)

Label-aware distance for clustering and visualization of single-cell data. The method uses temporal and spatial locality to control between-sample variability in longitudinal and multi-sample studies.

**Publication:** *Label-aware distance mitigates temporal and spatial variability for clustering and visualization of single-cell gene expression data.* Communications Biology (2024).<br>
[Paper](https://www.nature.com/articles/s42003-024-05988-y) · [Code](https://github.com/KChen-lab/lad)

### bindSC (2022)

Bi-order canonical correlation analysis for integrating measurements across single-cell modalities, including gene expression, chromatin accessibility, protein abundance, and spatial data.

**Publication:** *Bi-order multimodal integration of single-cell data.* Genome Biology (2022).<br>
[Paper](https://link.springer.com/article/10.1186/s13059-022-02679-x) · [Code](https://github.com/KChen-lab/bindSC)

### Single-cell CRISPR immune screens (2022)

Perturb-seq and CROP-seq combined with immune assays to study how tumor-intrinsic genes shape responses to T-cell killing and anti-PD-1 therapy. As co-first author, I analyzed transcriptional responses to perturbations and their relationships to immune phenotypes.

**Publication:** *Single-cell CRISPR immune screens reveal immunological roles of tumor intrinsic factors.* NAR Cancer (2022).<br>
[Paper](https://academic.oup.com/narcancer/article/4/4/zcac038/6884717)

### SCMER (2021)

I developed SCMER to select compact molecular feature panels while preserving cell-state organization and rare populations. It supports feature selection across single-cell assays, including RNA, chromatin, and protein measurements.

**Publication:** *Single-cell manifold-preserving feature selection for detecting rare cell populations.* Nature Computational Science (2021).<br>
[Paper](https://doi.org/10.1038/s43588-021-00070-7) · [Code](https://github.com/KChen-lab/scmer) · [Docs](https://scmer.readthedocs.io/en/latest/examples.html)

### EpiNB

A software package and web application for MHC-I antigen presentation prediction.

[Code](https://github.com/KChen-lab/epiNB) · [Web app](https://epinbweb.streamlit.app/)

### Sensei (2022)

Sample-size planning for studies of changes in cell-type abundance.

**Publication:** *Sensei: how many samples to tell a change in cell type abundance?* BMC Bioinformatics (2022).<br>
[Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04526-5) · [Web app](https://kchen-lab.github.io/sensei/table_beta.html)

### Stratified tests and weighted common-language effect size (2021)

Statistical methods for differential-expression analysis under batch effects, including a weighted common-language effect size for the van Elteren test.

**Publication:** *Stratified Test Accurately Identifies Differentially Expressed Genes Under Batch Effects in Single-Cell Data.* IEEE/ACM Transactions on Computational Biology and Bioinformatics (2021).<br>
[Paper](https://ieeexplore.ieee.org/abstract/document/9476999) · [Code](https://github.com/KChen-lab/stratified-tests-for-seurat)

### Cyclum (2020)

I developed Cyclum to infer latent periodic processes, such as cell-cycle progression, from single-cell expression data. Its circular representation helps distinguish periodic variation from other cell-state differences.

**Publication:** *Latent periodic process inference from single-cell RNA-seq data.* Nature Communications (2020).<br>
[Paper](https://www.nature.com/articles/s41467-020-15295-9) · [Code](https://github.com/KChen-lab/cyclum)
