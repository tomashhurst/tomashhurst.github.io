---
layout: page
title: Research - mapping dynamic immunity
permalink: /research/
---

---

![Research](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Research.png)

My research involves the development and application of a range of high-dimensional single-cell cytometry technologies and assays, as well as computational analysis approaches, to map dynamic immune responses over time, space, and disease. My team and I apply these approaches to the study of immunology and infectious disease, including emerging pathogens such as [SARS-CoV-2 and COVID-19](https://www.cell.com/cell-reports-medicine/fulltext/S2666-3791(21)00019-7), [Zika virus](https://jneuroinflammation.biomedcentral.com/articles/10.1186/s12974-019-1566-5) encephalitis, and [West Nile virus](https://jneuroinflammation.biomedcentral.com/articles/10.1186/1742-2094-9-246) encephalitis.

An overview of this work can be found in these key presentations:
- [Fluidigm Webinar](https://www.fluidigm.com/articles/presentation---mapping-dynamic-immunity-across-time-space-and-disease-state-using-high%E2%80%90dimensional-cytometry-technologies-and-analytics): *Mapping Immunity Across Time, Space and Disease State* (2020). 
- [Oz Single Cell webinar](https://youtu.be/poEDERGXrQw?t=3151): *Integration, exploration, and analysis of high-dimensional single-cell cytometry data using Spectre* (2020). 

<br />

### High-dimensional cytometry and imaging technologies ###

---

![HD](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Tech.png)

Critical to investigating complex immune responses to diseases is the capacity to measure cells at the single-cell level, measuring multiple features of the cell simultaneously. To address this, we develop and apply a variety of high-dimensional cytometry technologies and assays. We have developed novel technology platforms, such as our world first 10-laser ‘LSR-X’ platform developed with BD, and one of the first published 25 colour flow cytometry assays ([Ashhurst et al. 2017](https://currentprotocols.onlinelibrary.wiley.com/doi/abs/10.1002/cpim.37)). We also developed the first assays to be used on Australia’s first mass cytometer (CyTOF, [Ashhurst et al. 2019](https://link.springer.com/protocol/10.1007/978-1-4939-9454-0_12)), as well as Australia’s first Imaging Mass Cytometer (IMC, [SpectreMAP Github](https://github.com/ImmuneDynamics/SpectreMAP)). Most recently, we have implemented high-dimensional spectral cytometry platforms and panels, and performed comprehensive evaluations of both conventional and spectral cytometry ([Niewold\*, Ashhurst\* et al. 2020](https://onlinelibrary.wiley.com/doi/abs/10.1002/cyto.a.24211)). 

<br />

### Computational analysis approaches ###

---

![Comp](https://wiki.centenary.org.au/download/attachments/146080606/Screen%20Shot%202020-10-22%20at%2012.25.13%20pm.png?version=1&modificationDate=1603369521998&api=v2)

As the size and complexity of high-dimensional cytometry data continue to expand, comprehensive, scalable, and methodical computational analysis approaches are essential. Yet, contemporary clustering and dimensionality reduction tools alone are insufficient to analyse and integrate analyses across large numbers of samples, batches, or experiments. Moreover, analysis approaches that can adequately incorporate time-series data are lacking. Following a seed funding grant from the Marie Bashir Institute, I helped establish the ‘[Immune Dynamics](https://github.com/ImmuneDynamics)’ team, a collaborative group with a focus on the development of novel computational analysis tools to address these challenges. We have developed a number of computational analysis approaches, including Spectre, an R package that enables comprehensive end-to-end integration and analysis of high-dimensional cytometry data from different batches or experiments ([Ashhurst et al. 2020](https://www.biorxiv.org/content/10.1101/2020.10.22.349563v1.abstract)). To facilitate the analysis of time-series data, we also developed the time-series clustering using the ChronoClust algorithm ([Putri et al. 2019](https://www.sciencedirect.com/science/article/pii/S0950705119300796)). Most recently, we have adapted the Spectre package to facilitate spatial analysis of IMC data ([SpectreMAP Github](https://github.com/ImmuneDynamics/SpectreMAP)).

<br />

### Application to disease ###

---

![COVID](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Publication%202.png)

We apply our high-dimensional technologies and analysis approaches to study the immune response to inflammation and infectious disease. A particular focus has been the study of **immunopathology**, where the immune response to inflammation or infectious disease may be a significant driver of disease. Through a collaboration with the [Doherty Institute](https://www.doherty.edu.au/), we comprehensively profiled the immune response in a cohort of **COVID-19** patients. Our work demonstrated that patients with severe disease exhibited an excessive and hyper-activated immune response ([Koutsakos et al. 2021](https://www.cell.com/cell-reports-medicine/fulltext/S2666-3791(21)00019-7)). 

In mouse models of viral encephalitis, our work has demonstrated that inflammatory monocyte-derived macrophages which infiltrate into the brain contribute significantly to disease in Zika virus encephalitis ([Hayashida et al. 2019](https://jneuroinflammation.biomedcentral.com/articles/10.1186/s12974-019-1566-5)) and West Nile virus encephalitis ([Getts et al. 2012](https://jneuroinflammation.biomedcentral.com/articles/10.1186/1742-2094-9-246)), and that immune-modulatory therapies targeting inflammatory monocytes may inhibit this process ([Getts et al. 2014](https://stm.sciencemag.org/content/6/219/219ra7.short)). Our most recent work has demonstrated that viral encephalitis drives an inflammatory mobilisation of the haematopoietic system in the bone marrow, resulting in the generation of these pathogenic monocytes ([Ashhurst et al 2019](https://link.springer.com/protocol/10.1007/978-1-4939-9454-0_12), [Ashhurst 2020, Fluidigm webinar](https://www.fluidigm.com/articles/presentation---mapping-dynamic-immunity-across-time-space-and-disease-state-using-high%E2%80%90dimensional-cytometry-technologies-and-analytics)).

Through various collaborations, we have applied our approaches in a number of areas, such as IRF8 depletion ([Terry et al. 2015](https://www.karger.com/Article/Abstract/365972)), T cell exhaustion in LCMV infection ([Huber et al. 2017](https://jvi.asm.org/content/91/22/e01219-17.short)), VZV infection of NK cells ([Campbell et al. 2018](https://journals.plos.org/plospathogens/article?rev=1&id=10.1371/journal.ppat.1006999)), antibody-mediated cell subset depletion ([Jung et al. 2018](https://www.jimmunol.org/content/201/7/2176.abstract)), interferon-mediated lethality in LCMV infection ([Jung et al. 2020](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1008525&rev=1)), B cell responses in multiple sclerosis ([Marsh-Wakefield et al. 2020](https://onlinelibrary.wiley.com/doi/abs/10.1002/cti2.1133)), and intrapulmonary vaccination strategies ([Ferrell et al. 2021](https://doi.org/10.1038/s41385-021-00379-6)).

<br />

### Key links: ###

---

[**Publications**](https://tomashhurst.github.io/publications)

[**Spectre Home Page**](https://github.com/immunedynamics/spectre)

[**Contact info**](https://tomashhurst.github.io/about/)
