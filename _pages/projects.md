---
layout: page
title: research
permalink: /projects/
#description: research directions of the lab
nav: true
nav_order: 2
#display_categories: [work, fun]
horizontal: true
---

Our lab develops machine learning methods for high-dimensional, sparse, heterogeneous, and multimodal genomics data. Our work is motivated by a fundamental gap: while cellular and molecular systems are inherently complex and dynamic, experimental measurements often only provide partial and limited observations. To address this challenge, we develop network-based and deep learning approaches that integrate large-scale public datasets -- including both bulk and single-cell data -- along with prior biological knowledge. Our research interests fall roughly in the following categories:
- reconstruct multimodal representations of cells; 
- transfer experimental insights from model organisms to human contexts;
- identify genes and pathways underlying human diseases and sex differences.

<br>
## single-cell cross-modality prediction

Cellular function are coordinated through dynamic interactions among diverse molecular entities, including genes, proteins, and regulatory DNA elements. However, experimental technologies typically capture only partial, static snapshots of this complex regulatory landscape. Our lab develops deep learning methods that leverage large-scale public datasets to reconstruct multimodal cellular profiles and infer the dynamic relationships between molecular modalities, enabling a more comprehensive understanding of gene regulation and cellular state.

<div class="row">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/polarbear.png" title="Semi-supervised single-cell cross-modality translation model" class="img-fluid rounded" %}
  </div>
</div>

Selected publications: 
”Multimodal Single- Cell Translation and Alignment with Semi-Supervised Learning” Journal of Computational Biology (2022)
”Semi-supervised single-cell cross-modality translation using Polarbear” International Conference on Research in Computational Molecular Biology (2022)
”Multicondition and multimodality single-cell temporal profile inference during mouse embryonic development” Genome Research (2025, in press)

<br>
## transfer knowledge from model organisms to human

Model organisms – such as mouse, zebrafish – have been widely used to uncover molecular mechanisms relevant to human biology, particularly in contexts where human samples are scarce or inaccessible (e.g., the brain). However, evolutionary divergence between species poses significant challenges for direct knowledge transfer, often limiting the translational value of findings. Our lab develops network-based and deep learning approaches to project and contextualize experimental observations from model organisms, with the goal of improving our understanding of human health and disease.

<div class="row">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/icebear.png" title="Cross-species prediction of single-cell transcriptomic profiles" class="img-fluid rounded" %}
  </div>

  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/astrocytes.png" title="Human astrocyte-specific disease gene prediction leveraging mouse disease models and human public data" class="img-fluid rounded" %}
  </div>
</div>

Selected publications: 
”Identifying genes and pathways linking astrocyte regional specificity to Alzheimer’s disease susceptibility” bioRxiv
”Cross-species imputation and comparison of single-cell transcriptomic profiles” Genome Biology (2025)


<br>
## characterize complex human diseases

Complex diseases arise from the interplay of numerous genetic risk variants, environmental influences, and their context-dependent interactions across diverse biological systems. These conditions often present with heterogeneous phenotypes driven by coordinated dysregulation across multiple cell types and tissues. Our lab develops network-based approaches to systematically uncover genetic factors underlying complex disease etiology and to characterize their functional impact in tissue-specific, cell-type-specific, and single-cell contexts.

<div class="row">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/asd.png" title="Evidence-weighted network-based classifier for systematic autism gene prediction" class="img-fluid rounded" %}
  </div>
</div>

Selected publications: 
"Genome-wide autism gene prediction and functional characterization” Nature Neuroscience (2016)
"Lack of a site-specific phosphorylation of Presenilin 1 disrupts microglial gene networks and progenitors during development" PLoS One (2020)
