---
layout: resource
title: Spectre Home Page
permalink: /spectre-new/
---

![Spectre](https://raw.githubusercontent.com/tomashhurst/tomashhurst.github.io/master/images/Spectre.png)

**Introduction**

Spectre is an R package and computational toolkit that enables comprehensive end-to-end integration, exploration, and analysis of high-dimensional cytometry data from different batches or experiments. Spectre streamlines the analytical stages of raw data pre-processing, batch alignment, data integration, clustering, dimensionality reduction, visualisation and population labelling, as well as quantitative and statistical analysis; with a simple, clear, and modular design of analysis workflows, that can be utilised by data and laboratory scientists. The package was developed by Thomas Ashhurst (Sydney Cytometry Facility, The University of Sydney), Felix Marsh-Wakefield (Discipline of Pathology, The University of Sydney), and Givanna Putri (School of IT, The University of Sydney). For more information on the Spectre, check out the 'about Spectre' page or check out this talk. If you are interested in testing new 'development' functions in Spectre, or adding your own function, see the developers guide. 

**Citation**

If you use Spectre in your work, please consider citing Ashhurst TM, Marsh-Wakefield F, Putri GH et al. (2020). bioRxiv. 2020.10.22.349563. To continue providing open-source tools such as Spectre, it helps us if we can demonstrate that our efforts are contributing to analysis efforts in the community. Please also consider citing the authors of the individual packages or tools (e.g. CytoNorm, FlowSOM, tSNE, UMAP, etc) that are critical elements of your analysis work. We have provided some generic text that you can use for your methods section with each protocol and on the 'about' page.

<br />
<br />

## Getting started

---

<br />

<table class="table gmisc_table">
  <tbody>
    <tr style="border-top:2px solid grey">
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:700">
          <a href="pbmc3k_tutorial.html">Getting started with R
          </a>
        </div>
      </td>
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:700">
          <a href="multimodal_vignette.html">Installing Spectre
            </a>
        </div>
      </td>
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:700"><a href="spatial_vignette.html">Introductory Spectre tutorial
            </a>
        </div>
      </td>
    </tr>
    <tr>
      <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
          <img src="../output/images/pbmc3k_umap.jpg" width="3000">
      </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <img src="../output/images/citeseq_plot.jpg" width="3000">
        </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <img src="../output/images/spatial_vignette_ttr.jpg" width="3000">
        </td>
      </tr>
      <tr>
          <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">Instructions for installing R and RStudio, and a brief tutorial on their use for getting started.
          </td>
          <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">Installing Spectre.
          </td>
          <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">Spectre tutorial.
          </td>
     </tr>
      <tr>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
              <a class="btn btn-primary" href="pbmc3k_tutorial.html" role="button" style="width:100%">GO
              </a>
          </td>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-right:1px solid #000;text-align:left">
              <a class="btn btn-primary" href="multimodal_vignette.html" role="button" style="width:100%">GO
              </a>
          </td>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-right:1px solid #000;text-align:left">
              <a class="btn btn-primary" href="spatial_vignette.html" role="button" style="width:100%">GO
              </a>
          </td>
      </tr>
    </tbody>
</table>

<br />
<br />

## Technology-based workflows

---

<br />

<table class="table gmisc_table">
  <tbody>
    <tr style="border-top:2px solid grey">
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:700">
          <a href="pbmc3k_tutorial.html">Mass (CyTOF), flow, and spectral cytometry analysis
          </a>
        </div>
      </td>
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:700">
          <a href="multimodal_vignette.html">scRNAseq analysis</a>
        </div>
      </td>
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:700"><a href="spatial_vignette.html">Spatial analysis of IMC data</a>
        </div>
      </td>
    </tr>
    <tr>
      <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
          <img src="../output/images/pbmc3k_umap.jpg" width="3000">
      </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <img src="../output/images/citeseq_plot.jpg" width="3000">
        </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <img src="../output/images/spatial_vignette_ttr.jpg" width="3000">
        </td>
      </tr>
      <tr>
          <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">A basic overview of Seurat that includes an introduction to common analytical workflows.
          </td>
          <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">An introduction to working with multi-modal datasets in Seurat.
          </td>
          <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">Learn to explore spatially-resolved transcriptomic data with examples from 10x Visium and Slide-seq v2.
          </td>
     </tr>
      <tr>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
              <a class="btn btn-primary" href="pbmc3k_tutorial.html" role="button" style="width:100%">GO
              </a>
          </td>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-right:1px solid #000;text-align:left">
              <a class="btn btn-primary" href="multimodal_vignette.html" role="button" style="width:100%">GO
              </a>
          </td>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-right:1px solid #000;text-align:left">
              <a class="btn btn-primary" href="spatial_vignette.html" role="button" style="width:100%">GO
              </a>
          </td>
      </tr>
    </tbody>
</table>

## XXXXX

---

<br />

<table class="table gmisc_table">
  <tbody>
    <tr style="border-top:1px solid grey">
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:300;color:#00003f">Getting started with R
        </div>
      </td>
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:300;color:#00003f">Installing Spectre
        </div>
      </td>
      <td style="padding-left:.75em;width:30%;border-top:2px solid grey;border-right:1px solid #000;text-align:left">
        <div style="text-align:center;font-size:large;font-weight:300;color:#00003f">Spectre tutorial
        </div>
      </td>
    </tr>
    <tr>
      <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
          <br />
      </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <br />
        </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <br />
        </td>
     </tr>
    <tr>
      <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
          <img src="https://www.r-project.org/logo/Rlogo.svg" width="3000">
      </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <img src="https://raw.githubusercontent.com/ImmuneDynamics/Spectre/master/image/Spectre.png" width="3000">
        </td>
        <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">
            <img src="https://raw.githubusercontent.com/ImmuneDynamics/Spectre/master/image/Spectre.png" width="3000">
        </td>
      </tr>
      <tr>
          <td style="padding-left:.75em;width:30%;border-left:1px solid #000;border-right:1px solid #000;text-align:left">Instructions for installing R and RStudio, and a brief tutorial on their use for getting started.
          </td>
          <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">Installing Spectre.
          </td>
          <td style="padding-left:.75em;width:30%;border-right:1px solid #000;text-align:left">Spectre tutorial.
          </td>
     </tr>
      <tr>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-left:1px solid #000;border-right:1px solid #000;text-align:left">
              <div style="text-align:center;font-size:large;font-weight:700;color:#00003f">
                  <a href="https://tomashhurst.github.io/resources/flow"><b>GO TO PAGE</b></a>
              </div>
          </td>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-right:1px solid #000;text-align:left">
              <div style="text-align:center;font-size:large;font-weight:700;color:#00003f">
                  <a href="https://tomashhurst.github.io/resources/mass"><b>GO TO PAGE</b></a>
              </div>
          </td>
          <td style="padding-left:.75em;width:30%;border-bottom:2px solid grey;border-right:1px solid #000;text-align:left">
              <div style="text-align:center;font-size:large;font-weight:700;">
                  <p style="color:#00003f">
                      <a href="https://tomashhurst.github.io/resources/imc"><b>GO TO PAGE</b></a>
                  </p>
              </div>
          </td>
      </tr>
    </tbody>
</table>

<br />
<br />

<p style="color:grey"><i>Code for the table structure adapted from https://satijalab.org/seurat</i></p>
