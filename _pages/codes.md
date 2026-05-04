## SeismicPhaseAnalysis

<div class="row">
  <div class="col-sm-4">
    <div class="repositories">
      {% include repository/repo.liquid repository="arohatgi29/SeismicPhaseAnalysis" %}
    </div>
  </div>
  <div class="col-sm-8">
    A collection of tools for analyzing and stabilizing seismic phase. The repository implements circular-statistics based methods to characterize phase variability in seismic data, quantify wavefield coherence, and design phase-stabilization workflows for multichannel recordings.
  </div>
</div>

**Paper 1:** Rohatgi, A., Bakulin, A., and Fomel, S., 2025, Data-driven analysis of seismic phase using circular statistics: *The Leading Edge*, 44(9), 683–691. \[[DOI](https://doi.org/10.1190/tle44090683.1)\] \[[Paper](../assets/pdf/TLE_2025.pdf)\]

<div id="fig-viewer" style="margin-top: 12px;">
  <div style="display: flex; align-items: center; gap: 12px; margin-bottom: 8px;">
    <button onclick="changeFig(-1)" style="padding: 4px 12px; cursor: pointer;">&#8592;</button>
    <span id="fig-label" style="font-size: 13px; color: gray;">Figure 1 of 8</span>
    <button onclick="changeFig(1)" style="padding: 4px 12px; cursor: pointer;">&#8594;</button>
  </div>
  <img id="fig-img" src="/assets/img/publication_preview/Paper1/Figure1.jpg" style="width: 50%; border-radius: 8px; border: 0.5px solid var(--color-border-tertiary);" />
</div>

<script>
  var figIndex = 1;
  var figTotal = 8;
  function changeFig(dir) {
    figIndex = ((figIndex - 1 + dir + figTotal) % figTotal) + 1;
    document.getElementById('fig-img').src = '/assets/img/publication_preview/Paper1/Figure' + figIndex + '.jpg';
    document.getElementById('fig-label').innerText = 'Figure ' + figIndex + ' of ' + figTotal;
  }
</script>