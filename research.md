---
layout: page
title: Research - mapping dynamic immunity
permalink: /research/
---

---

![Research](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Research.png)

**Overview**: my research involves the development and application of a range of [high-dimensional single-cell cytometry/imaging technologies and assays](https://tomashhurst.github.io/research/#high-dimensional-cytometry-and-imaging-technologies), as well as [computational analysis approaches](https://tomashhurst.github.io/research/#computational-analysis-approaches), to map dynamic immune responses over time, space, and disease. My team and I collaboratively apply these approaches to the study of immunology and infectious disease, including emerging pathogens such as [SARS-CoV-2 and COVID-19](https://tomashhurst.github.io/research/#application-to-disease), [Zika virus](https://tomashhurst.github.io/research/#application-to-disease) encephalitis, and [West Nile virus](https://tomashhurst.github.io/research/#application-to-disease) encephalitis. 

Presentations on this work can be found in this [Fluidigm Webinar](https://www.fluidigm.com/articles/presentation---mapping-dynamic-immunity-across-time-space-and-disease-state-using-high%E2%80%90dimensional-cytometry-technologies-and-analytics) (Mapping Immunity Across Time, Space and Disease State, 2020) or this [Oz Single Cell webinar](https://youtu.be/poEDERGXrQw?t=3151) (Integration, exploration, and analysis of high-dimensional single-cell cytometry data using Spectre, 2020). 

**This work is summarised in four areas**:
1. [High-dimensional cytometry and imaging technologies](https://tomashhurst.github.io/research/#high-dimensional-cytometry-and-imaging-technologies)
2. [Computational analysis approaches](https://tomashhurst.github.io/research/#computational-analysis-approaches)
3. [Application to disease](https://tomashhurst.github.io/research/#application-to-disease)
4. [Engagement in the Human Cell Atlas (HCA) and other communities](https://tomashhurst.github.io/research/#engagement-in-the-human-cell-atlas-and-other-communities)

<br />

### High-dimensional cytometry and imaging technologies ###

---

![HD](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Tech.png)

Critical to investigating complex immune responses to disease is the capacity to measure cells at the single-cell level, examining multiple features of the cell simultaneously. To address this, we develop and apply a variety of high-dimensional cytometry technologies and assays. We have developed novel technology platforms, such as our world first [10-laser ‘LSR-X’ platform](https://sydneycytometry.org.au/hdflow) developed with BD, and one of the first published 25 colour flow cytometry assays ([Ashhurst et al. 2017](https://currentprotocols.onlinelibrary.wiley.com/doi/abs/10.1002/cpim.37)). We also developed the first assays to be used on [Australia’s first mass cytometer (CyTOF)](https://www.immunology.org.au/files/Newsletter_pdfs/ASI_NL_March_2015.pdf) ([Ashhurst et al. 2019](https://link.springer.com/protocol/10.1007/978-1-4939-9454-0_12)), as well as Australia’s first Imaging Mass Cytometer (IMC, [SpectreMAP Github](https://github.com/ImmuneDynamics/SpectreMAP)). Most recently, we have implemented high-dimensional spectral cytometry platforms and panels, and performed comprehensive evaluations of both conventional and spectral cytometry ([Niewold\*, Ashhurst\* et al. 2020](https://onlinelibrary.wiley.com/doi/abs/10.1002/cyto.a.24211)). 

<br />

### Computational analysis approaches ###

---

![Comp](https://wiki.centenary.org.au/download/attachments/146080606/Screen%20Shot%202020-10-22%20at%2012.25.13%20pm.png?version=1&modificationDate=1603369521998&api=v2)

As the size and complexity of high-dimensional cytometry data continue to expand, comprehensive, scalable, and methodical computational analysis approaches are essential. Yet, contemporary clustering and dimensionality reduction tools alone are insufficient to analyse and integrate analyses across large numbers of samples, batches, or experiments. Moreover, analysis approaches that can adequately incorporate time-series data are lacking. Following a seed funding grant from the [Marie Bashir Institute for Infectious Diseases and Biosecurity](https://www.sydney.edu.au/marie-bashir-institute/) (*"Mapping dynamic immunity: next-generation computational approaches to track the evolution of immune responses in West Nile virus and Zika virus encephalitis"*), we established the ‘[Immune Dynamics](https://github.com/ImmuneDynamics)’ team, a collaborative group with a focus on the development of novel computational analysis tools to address these challenges. 

My team and I have developed a number of computational analysis approaches, including [SPECTRE](https://wiki.centenary.org.au/display/SPECTRE), an R package that enables comprehensive end-to-end integration and analysis of high-dimensional cytometry data from different batches or experiments ([Ashhurst\*,  Marsh-Wakefield\*, Putri\* et al. bioRxiv. 2020](https://www.biorxiv.org/content/10.1101/2020.10.22.349563v1.abstract)). To facilitate the analysis of time-series data, we have also developed a number of time-series clustering algorithms, including [ChronoClust](https://github.com/ghar1821/Chronoclust) ([Putri et al. 2019](https://www.sciencedirect.com/science/article/pii/S0950705119300796)) and [TrackSOM](https://github.com/ghar1821/TrackSOM), which we recently applied to the study of COVID-19 ([Koutsakos et al. 2021](https://www.cell.com/cell-reports-medicine/fulltext/S2666-3791(21)00019-7)). We have also developed novel multi-perspective methods for the evaluation of clustering algorithms ([Putri et al. 2021](https://doi.org/10.1093/bioinformatics/btab038)). Most recently, we have adapted the Spectre package to facilitate spatial analysis of IMC data ([SpectreMAP Github](https://github.com/ImmuneDynamics/SpectreMAP)). Our ongoing work is focused on the development of better data integration approaches and spatial analysis tools.

<br />

### Application to disease ###

---

![COVID](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Publication%202.png)

We apply our high-dimensional technologies and analysis approaches to study inflammation and infectious disease. A particular focus has been the study of *immunopathology*, where the immune response to infection may be a significant driver of disease. 

**SARS-CoV-2 and COVID-19**

Through a collaboration with the [Doherty Institute](https://www.doherty.edu.au/) and the [University of Melbourne](https://www.unimelb.edu.au/), we comprehensively profiled the immune response to [SARS-CoV-2](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) in a cohort of [COVID-19](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) patients. Our work demonstrated that patients with severe disease exhibited an excessive and hyper-activated immune response ([Koutsakos et al. 2021](https://www.cell.com/cell-reports-medicine/fulltext/S2666-3791(21)00019-7)). To study the kinetics of this immune response, we also developed and applied a novel time-series analysis approached called [TrackSOM](https://github.com/ghar1821/TrackSOM). This study has been featured on [Doherty Instite News](https://www.doherty.edu.au/news-events/news/mapping-an-effective-immune-response-to-covid-19), [Medical Xpress](https://medicalxpress.com/news/2021-02-effective-immune-response-covid-.html), the [Herald Sun](https://www.heraldsun.com.au/coronavirus/melbourne-experts-uncover-why-covid-affects-people-differently/news-story/ed5ffb9604c1b4db776503562e494f71), and [Ticker](https://twitter.com/tickerNEWSau/status/1359991653243572224?s=20).

- Panel design and analysis protocols that may be helpful in COVID-19 research can be found on the [resources](https://tomashhurst.github.io/resources) page.

**Zika and West Nile virus encephalitis and immune modulation**

In mouse models of viral encephalitis, our work has demonstrated that inflammatory monocyte-derived macrophages which infiltrate into the brain contribute significantly to disease in [Zika virus](https://www.who.int/news-room/fact-sheets/detail/zika-virus) encephalitis ([Hayashida et al. 2019](https://jneuroinflammation.biomedcentral.com/articles/10.1186/s12974-019-1566-5)) and [West Nile virus](https://www.who.int/news-room/fact-sheets/detail/west-nile-virus) encephalitis ([Getts et al. 2012](https://jneuroinflammation.biomedcentral.com/articles/10.1186/1742-2094-9-246)), and that *immune-modulatory therapies* targeting inflammatory monocytes may inhibit this process ([Getts et al. 2014](https://stm.sciencemag.org/content/6/219/219ra7.short)). This work was featured on [ABC News](http://www.abc.net.au/science/articles/2014/01/16/3926376.htm) and [The Guardian](http://www.theguardian.com/world/2014/jan/16/heart-attack-damage-can-be-reduced-with-a-simple-injection-say-experts). Our most recent work has demonstrated that viral encephalitis drives an *inflammatory mobilisation of the haematopoietic system* in the bone marrow, resulting in the generation of these pathogenic monocytes ([Ashhurst et al 2019](https://link.springer.com/protocol/10.1007/978-1-4939-9454-0_12), [Ashhurst 2020, Fluidigm webinar](https://www.fluidigm.com/articles/presentation---mapping-dynamic-immunity-across-time-space-and-disease-state-using-high%E2%80%90dimensional-cytometry-technologies-and-analytics)).

**Immunology**

Through various collaborations, we have applied our approaches in a number of areas, such as IRF8 depletion ([Terry et al. 2015](https://www.karger.com/Article/Abstract/365972)), T cell exhaustion in LCMV infection ([Huber et al. 2017](https://jvi.asm.org/content/91/22/e01219-17.short)), VZV infection of NK cells ([Campbell et al. 2018](https://journals.plos.org/plospathogens/article?rev=1&id=10.1371/journal.ppat.1006999)), antibody-mediated cell subset depletion ([Jung et al. 2018](https://www.jimmunol.org/content/201/7/2176.abstract)), interferon-mediated lethality in LCMV infection ([Jung et al. 2020](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1008525&rev=1)), B cell responses in multiple sclerosis ([Marsh-Wakefield et al. 2020](https://onlinelibrary.wiley.com/doi/abs/10.1002/cti2.1133)), and intrapulmonary vaccination strategies ([Ferrell et al. 2021](https://doi.org/10.1038/s41385-021-00379-6)).

<br />

### Engagement in the Human Cell Atlas and other communities ###

---

![HCA](https://github.com/tomashhurst/tomashhurst.github.io/blob/master/images/HCA%20wide.png?raw=true)

We are actively involved in the [Human Cell Atlas (HCA)](https://www.humancellatlas.org/) community, including attendance at HCA general meetings in [Hinxton, UK (2018)](https://github.com/tomashhurst/tomashhurst.github.io/blob/master/images/HCA_hinxton.jpg?raw=true), and [Tokyo, Japan (2019)](https://youtu.be/xYqd2w_aRH0?t=327), seeking to help define the contribution of high-dimensional cytometry and imaging technologies to the HCA objectives. We also presented on Spectre, one of our computational tools, at the [HCA Asia meeting](https://youtu.be/95dy_p5FFck?t=15491) (virtual) in 2020.

<br />

### Key links: ###

---

[**Publications**](https://tomashhurst.github.io/publications)

[**Spectre Home Page**](https://wiki.centenary.org.au/display/SPECTRE)

[**Contact info**](https://tomashhurst.github.io/about/)
