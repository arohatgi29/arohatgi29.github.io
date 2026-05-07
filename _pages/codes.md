---
layout: page
permalink: /codes/
title: Codes
nav: true
nav_order: 5
---

<style>
  /* Make repo cards fill their column */
  .repositories .repo-card,
  .repositories .repo,
  .repositories iframe,
  .repositories img {
    width: 100% !important;
    max-width: 100% !important;
  }
  /* Optional: bump the font size inside the card */
  .repositories {
    font-size: 1.05rem;
  }
  /* Add a bit of vertical breathing room between the card and description on small screens */
  @media (max-width: 575.98px) {
    .repositories {
      margin-bottom: 1rem;
    }
  }
</style>

## SeismicPhaseStatistics

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo_static.liquid repository="arohatgi29/SeismicPhaseStatistics" %}
    </div>
  </div>
  <div class="col-sm-6">
    A collection of tools for analyzing and stabilizing seismic phase. The repository implements circular-statistics based methods to characterize phase variability in seismic data, quantify wavefield coherence, and design phase-stabilization workflows for multichannel recordings.
  </div>
</div>

**Rohatgi-et-al-2025-Data-driven analysis of seismic phase using circular statistics** [![Code](https://img.shields.io/badge/Code-GitHub-2ea44f)](https://github.com/arohatgi29/SeismicPhaseStatistics/tree/main/Rohatgi-et-al-2025-TLE)

---

## Seismic Processing using Madagascar

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo_static.liquid repository="arohatgi29/Seismic-Processing-using-Madagascar" %}
    </div>
  </div>
  <div class="col-sm-6">
    A tutorial for end-to-end seismic processing of a 2D line using <a href="https://ahay.org/wiki/Main_Page">Madagascar</a>, an open-source software package for geophysical data analysis. The workflow covers: fetching data, setting geometry, first break mute, ground roll attenuation, surface consistent amplitude correction, velocity analysis and NMO, stack, and Stolt's migration.
  </div>
</div>

---
## LocalSignalAttributes.jl

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo_static.liquid repository="arohatgi29/LocalSignalAttributes.jl" %}
    </div>
  </div>
  <div class="col-sm-6">
    A registered Julia package for computing <em>local</em> signal attributes, measures defined in the neighborhood of each sample rather than instantaneously or globally, using regularized inversion with shaping regularization. Useful for estimating local frequencies and local similarity between datasets, with applications in seismic signal analysis.
  </div>
</div>
[![JuliaHub](https://img.shields.io/badge/JuliaHub-LocalSignalAttributes-9558B2?logo=julia&logoColor=white)](https://juliahub.com/ui/Packages/General/LocalSignalAttributes)

---

## Hackathon on Computational Reproducibility

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo_static.liquid repository="arohatgi29/Team_Surfers_Geoscience_Hackathon2024" %}
    </div>
  </div>
  <div class="col-sm-6">
    Winner of the <a href="https://www.jsg.utexas.edu/geoscience-hackathon/past-hackathons/">JSG Geoscience Hackathon</a> on Computational Reproducibility (Jackson School of Geosciences, UT Austin). With Team Surfers, I reproduced Raissi et al. (2019) on Physics-Informed Neural Networks (PINNs), benchmarked CPU vs. GPU implementations, ran sensitivity analyses on network depth and width for the 1+1D Burgers' equation, and extended the framework to solve the 1D and 2D wave equations under Dirichlet and Neumann boundary conditions.
  </div>
</div>

---
<!-- 
## Personal Website

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo.liquid repository="arohatgi29/arohatgi29.github.io" %}
    </div>
  </div>
  <div class="col-sm-6">
     Source code for this website, built with <a href="https://github.com/alshedivat/al-folio">al-folio</a>, a Jekyll theme for academics, and hosted on GitHub Pages. The site brings together my research, publications, code, CV, and outdoor activities in one place, and serves as a living portfolio that I update as new work and experiences come along.
  </div>
</div> -->