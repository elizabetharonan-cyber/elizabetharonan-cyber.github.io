---
layout: page
title: Research Articles
permalink: /publications/
description: Publications by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 2
---

{% include research_nav.liquid %}

<!-- External Profiles -->
<div style="margin-bottom: 2rem; padding: 1rem 1.5rem; background-color: var(--global-bg-color); border: 1px solid var(--global-divider-color); border-radius: 6px; display: flex; align-items: center; gap: 2rem; flex-wrap: wrap;">
  <h4 style="margin: 0; font-size: 1rem;">External Profiles</h4>
  <a href="https://www.ncbi.nlm.nih.gov/myncbi/1niJzd-Lz-oAF/bibliography/public/" target="_blank" rel="noopener noreferrer" style="display: flex; align-items: center; text-decoration: none;">
    <i class="ai ai-pubmed" style="font-size: 1.5rem; margin-right: 0.4rem;"></i> NCBI Bibliography
  </a>
  <a href="https://scholar.google.com/citations?hl=en&user=8YQwM9IAAAAJ" target="_blank" rel="noopener noreferrer" style="display: flex; align-items: center; text-decoration: none;">
    <i class="ai ai-google-scholar" style="font-size: 1.5rem; margin-right: 0.4rem;"></i> Google Scholar
  </a>
  <a href="https://orcid.org/0000-0001-7400-5718" target="_blank" rel="noopener noreferrer" style="display: flex; align-items: center; text-decoration: none;">
    <i class="ai ai-orcid" style="font-size: 1.5rem; margin-right: 0.4rem;"></i> ORCID
  </a>
</div>

<!-- Two-column layout: PhD | Postdoc -->
<div style="display: flex; gap: 2.5rem; align-items: flex-start; flex-wrap: wrap;">

  <!-- Left Column: PhD -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="color: var(--global-theme-color); border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.4rem; margin-bottom: 0.5rem;"><em>C. elegans</em> Sensory Biology (Xu Lab, PhD)</h3>
    <div class="publications">
    {% bibliography --file papers --query @*[author ~= Xu] --sort year --order descending %}
    </div>
  </div>

  <!-- Right Column: Postdoc + MS -->
  <div style="flex: 1; min-width: 300px;">
    <h3 style="color: var(--global-theme-color); border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.4rem; margin-bottom: 0.5rem;">Orofacial Somatosensation (Emrick Lab, Postdoc)</h3>
    <div class="publications">
    {% bibliography --file papers --query @*[author ~= Emrick] --sort year --order descending %}
    </div>

    <h3 style="color: var(--global-theme-color); border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.4rem; margin-top: 2.5rem; margin-bottom: 0.5rem;">Tissue Engineering (Larkin Lab, MS)</h3>
    <div class="publications">
    {% bibliography --file papers --query @*[author ~= Larkin] --sort year --order descending %}
    </div>
  </div>

</div>
