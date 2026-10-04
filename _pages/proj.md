---
layout: archive
title: "Projects"
permalink: /proj/
author_profile: true
redirect_from:
  - /proj
---

## TissueNarrator (2025)
Generative modeling of spatial transcriptomics with large language models: tissue sections are represented as "spatial sentences" so an LLM can learn spatially conditioned gene expression.

![TissueNarrator overview](/images/tissuenarrator.png)

- Use cases: generating realistic cell profiles, predicting intercellular interactions, in silico perturbation (MERFISH, Visium HD, Perturb-FISH, ...)
- Preprint: ["TissueNarrator: Generative Modeling of Spatial Transcriptomics with Large Language Models." bioRxiv (2025).](https://www.biorxiv.org/content/10.1101/2025.11.24.690325v1)
- Python package: https://github.com/ma-compbio-lab/TissueNarrator

## Steamboat (2025)
Attention-based, interpretable decomposition of a cell's gene expression into intrinsic programs, neighboring-cell communication, and long-range interactions.

![Steamboat overview](/images/steamboat.png)

- Use cases: spatial omics (MERFISH, CosMx, Visium, CODEX, ...)
- Preprint: ["Steamboat: Attention-based multiscale delineation of cellular interactions in tissues." bioRxiv (2025).](https://www.biorxiv.org/content/10.1101/2025.04.06.647437v1)
- Python package: https://github.com/ma-compbio/Steamboat
- Documentation: https://steamboat.readthedocs.io/en/latest/

## LAD (2024)
Label-aware distance for clustering and visualization of single-cell data, using the temporal/spatial locality of batch effects to control for between-sample variability.
- Use cases: longitudinal and multi-sample scRNA-seq
- Publication: ["Label-aware distance mitigates temporal and spatial variability for clustering and visualization of single-cell gene expression data." Communications Biology 7 (2024): 326.](https://www.nature.com/articles/s42003-024-05988-y)
- Code: https://github.com/KChen-lab/lad

## bindSC (2022)
Bi-order canonical correlation analysis (bi-CCA) for integrating single-cell data across different modalities.
- Use cases: integrating any two single-cell modalities (e.g., scRNA-seq, scATAC-seq, CyTOF, spatial)
- Publication: ["Bi-order multimodal integration of single-cell data." Genome Biology 23 (2022): 112.](https://link.springer.com/article/10.1186/s13059-022-02679-x)
- R package: https://github.com/KChen-lab/bindSC

## Single-cell CRISPR immune screens (2022)
Perturb-seq and CROP-seq combined with immune assays to study how tumor-intrinsic genes shape responses to T cell killing and anti-PD-1 therapy.
- Publication: ["Single-cell CRISPR immune screens reveal immunological roles of tumor intrinsic factors." NAR Cancer 4.4 (2022): zcac038.](https://academic.oup.com/narcancer/article/4/4/zcac038/6884717)

## SCMER (2021)
Manifold based feature selection.
- Use cases: single-cell assays (scRNA-seq, scATAC-seq, CITE-seq, CyTOF, ...)
- Publication: ["Single-cell manifold-preserving feature selection for detecting rare cell populations." Nature Computational Science 1.5 (2021): 374-384.](https://rdcu.be/ckZGT)
- Python package (and R wrapper): https://github.com/KChen-lab/scmer
- Tutorials: https://scmer.readthedocs.io/en/latest/examples.html

## EpiNB (2022)
A package for MHC-I antigen presentation prediction.
- web app: https://epinbweb.streamlit.app/
- Python package: https://github.com/KChen-lab/epiNB

## Sensei (2021)
- Publication: ["Sensei: how many samples to tell a change in cell type abundance?." BMC bioinformatics 23 (2022): 1-22.](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-021-04526-5)
- web app: https://kchen-lab.github.io/sensei/table_beta.html

## Weighted common-language effect size for the van Elteren Test (2020)
- Publication: ["Stratified Test Accurately Identifies Differentially Expressed Genes Under Batch Effects in Single-Cell Data." IEEE/ACM transactions on computational biology and bioinformatics 18.6 (2021): 2072-2079.](https://ieeexplore.ieee.org/abstract/document/9476999)
- R code: https://github.com/KChen-lab/stratified-tests-for-seurat

## Cyclum (2019)
- Publication: ["Latent periodic process inference from single-cell RNA-seq data." Nature communications 11.1 (2020): 1441.](https://www.nature.com/articles/s41467-020-15295-9)
- Python package: https://github.com/KChen-lab/cyclum
