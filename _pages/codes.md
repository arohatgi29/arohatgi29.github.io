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

## SeismicPhaseAnalysis

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo.liquid repository="arohatgi29/SeismicPhaseAnalysis" %}
    </div>
  </div>
  <div class="col-sm-6">
    A collection of tools for analyzing and stabilizing seismic phase. The repository implements circular-statistics based methods to characterize phase variability in seismic data, quantify wavefield coherence, and design phase-stabilization workflows for multichannel recordings.
  </div>
</div>

**Rohatgi-et-al-2025-Data-driven-analysis-of-seismic-phase-using-circular-statistics** [![Code](https://img.shields.io/badge/Code-GitHub-2ea44f)](https://github.com/arohatgi29/SeismicPhaseAnalysis)

---

## Seismic Processing using Madagascar

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo.liquid repository="arohatgi29/Seismic-Processing-using-Madagascar" %}
    </div>
  </div>
  <div class="col-sm-6">
    A tutorial for end-to-end seismic processing of a 2D line using <a href="https://ahay.org/wiki/Main_Page">Madagascar</a>, an open-source software package for geophysical data analysis. The workflow covers: fetching data, setting geometry, first break mute, ground roll attenuation, surface consistent amplitude correction, velocity analysis and NMO, stack, and Stolt's migration.
  </div>
</div>

---

## Hackathon on Computational Reproducibility

<div class="row align-items-center">
  <div class="col-sm-6">
    <div class="repositories w-100">
      {% include repository/repo.liquid repository="arohatgi29/Team_Surfers_Geoscience_Hackathon2024" %}
    </div>
  </div>
  <div class="col-sm-6">
    Winner of the <a href="https://www.jsg.utexas.edu/geoscience-hackathon/past-hackathons/">JSG Geoscience Hackathon</a> on Computational Reproducibility, hosted by the Jackson School of Geosciences, University of Texas at Austin. The hackathon challenged teams to develop reproducible geoscientific workflows. Our team, Team Surfers, built a reproducible seismic processing pipeline.
  </div>
</div>