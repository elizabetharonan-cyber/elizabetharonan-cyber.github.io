---
layout: page
title: Preprints
permalink: /preprints/
description: Preprints by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 3
---

{% include research_nav.liquid %}

<div style="display: flex; align-items: center; gap: 2rem; margin-bottom: 2.5rem; padding: 1.5rem 2rem; background: linear-gradient(135deg, var(--global-bg-color) 0%, var(--global-code-bg-color) 100%); border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); border-left: 4px solid var(--global-theme-color); flex-wrap: wrap;">
  <div style="flex-shrink: 0;">
    <img src="{{ '/assets/img/teach.PNG' | relative_url }}" alt="Elizabeth presenting" style="width: 160px; height: 160px; object-fit: cover; border-radius: 50%; box-shadow: 0 3px 10px rgba(0,0,0,0.15);" />
  </div>
  <div style="flex: 1; min-width: 200px;">
    <p style="font-size: 1.5rem; font-weight: 700; margin: 0 0 0.5rem 0; color: var(--global-theme-color);">Sneak peek at what's coming next.</p>
    <p style="font-size: 1.1rem; line-height: 1.6; margin: 0; color: var(--global-text-color);">These preprints showcase my current research trajectory and ongoing projects.</p>
  </div>
</div>

<div class="publications">
{% bibliography --file preprints --sort year --order descending %}
</div>
