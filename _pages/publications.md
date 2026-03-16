---
layout: page
title: Research Articles
permalink: /publications/
description: Publications by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 2
---

{% include research_nav.liquid %}

{% include external_profiles.liquid %}

<h3 style="color: var(--global-theme-color); border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.4rem; margin-bottom: 0.5rem;">Orofacial Somatosensation (Emrick Lab, Postdoc)</h3>
<div class="publications">
{% bibliography --file papers --query @*[author ~= Emrick] --sort year --order descending %}
</div>

<h3 style="color: var(--global-theme-color); border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.4rem; margin-top: 2.5rem; margin-bottom: 0.5rem;"><em>C. elegans</em> Sensory Biology (Xu Lab, PhD)</h3>
<div class="publications">
{% bibliography --file papers --query @*[author ~= Xu] --sort year --order descending %}
</div>

<h3 style="color: var(--global-theme-color); border-bottom: 2px solid var(--global-theme-color); padding-bottom: 0.4rem; margin-top: 2.5rem; margin-bottom: 0.5rem;">Tissue Engineering (Larkin Lab, MS)</h3>
<div class="publications">
{% bibliography --file papers --query @*[author ~= Larkin] --sort year --order descending %}
</div>
