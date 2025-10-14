---
layout: page
title: research
permalink: /projects/
#description: research directions of the lab
nav: true
nav_order: 1
#display_categories: [work, fun]
horizontal: true
---

Our lab develops machine learning methods for high-dimensional, sparse, heterogeneous, and multimodal genomics data. Our work is motivated by the gap that while cellular and molecular systems are highly complex and dynamic, individual experimental data often capture partial and limited snapshots of biological processes. To address this challenge, we develop network-based and deep learning approaches that integrate large-scale public datasets, including both bulk and single-cell data, along with prior biological knowledge. Our research interests lies in the following areas:
- predicting multimodal representations of cells; 
- transfering experimental insights from model organisms to human contexts;
- identifying genes and pathways underlying human diseases and sex differences.

<br>
## multimodal machine learning for biology

Biological systems can be represented through diverse assay types, or data modalities, each capturing a unique layer of molecular information and representing a partial view of the underlying system. Although biological processes and disease progression are inherently dynamic and involve multiple molecular layers, most high-throughput measurements capture only static snapshots. Our lab develops deep learning models that integrate large-scale public omics datasets to reconstruct multimodal cellular states and infer dynamic relationships across data modalities.

<div class="text-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/polarbear.png" title="Semi-supervised single-cell cross-modality translation model" class="img-fluid rounded" style="width:80%;" %}
  </div>
</div>

Selected publications: 
- [”Semi-supervised single-cell cross-modality translation using Polarbear”](https://link.springer.com/chapter/10.1007/978-3-031-04749-7_2)
- [”Multimodal Single- Cell Translation and Alignment with Semi-Supervised Learning”](https://pubmed.ncbi.nlm.nih.gov/36251758/)
- [”Multicondition and multimodality single-cell temporal profile inference during mouse embryonic development”](https://genome.cshlp.org/content/35/10/2339.long)

<br>
<br>
## network-guided discovery of human disease genes

Biological systems operate through complex networks of interacting molecules that vary across tissues and cell types. We design network-based models to integrate multimodal omics data, uncover molecular interactions, and identify genetic drivers of disease in their specific biological contexts.

<div class="text-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/asd.png" title="Evidence-weighted network-based classifier for systematic autism gene prediction" class="img-fluid rounded" %}
  </div>
</div>

Selected publications: 
- ["Genome-wide autism gene prediction and functional characterization”](https://www.nature.com/articles/nn.4353)
- ["Lack of a site-specific phosphorylation of Presenilin 1 disrupts microglial gene networks and progenitors during development"](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0237773)
- ["Astrocyte-derived extracellular matrix proteins regulate synapse remodeling in stress-induced depression"](https://www.biorxiv.org/content/10.1101/2024.12.30.630684v1)

<br>
<br>

## knowledge transfer across species

Model organisms, such as mice, have been widely used to uncover molecular mechanisms relevant to human biology and diseases, especially when human samples are limited or inaccessible (e.g., the brain). However, evolutionary divergence between species create challenges for direct knowledge transfer, often limiting the translational value of findings. Our lab develops network and deep learning models to align, project, and contextualize data from model organisms, with the goal of improving data-driven insights into human disease.

<div class="text-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/icebear.png" title="Cross-species prediction of single-cell transcriptomic profiles" class="img-fluid rounded" style="width:70%;" %}
  </div>

</div>

Selected publications: 
- [”Cross-species imputation and comparison of single-cell transcriptomic profiles”](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-025-03493-x)
- [”Identifying genes and pathways linking astrocyte regional specificity to Alzheimer’s disease susceptibility”](https://www.biorxiv.org/content/10.1101/2022.11.16.515390v1)

