---
layout: default
title: Preprints
permalink: /preprints/
description: Preprints by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 3
---

<div style="margin-bottom: 2rem; padding: 1rem; background-color: var(--global-bg-color); border-left: 3px solid var(--global-theme-color);">
  <strong>Publication Types:</strong>
  <a href="/publications/" style="margin-left: 1rem;">Research Articles</a> |
  <a href="/preprints/" style="margin-left: 0.5rem;">Preprints</a> |
  <a href="/reviews/" style="margin-left: 0.5rem;">Reviews & Commentaries</a> |
  <a href="/protocols/" style="margin-left: 0.5rem;">Protocols</a>
</div>

Take a sneak peek at articles coming soon! These preprints showcase some of my current research trajectory and ongoing projects.

<div class="publications">
{% bibliography --file preprints --sort year --order descending %}
</div>
