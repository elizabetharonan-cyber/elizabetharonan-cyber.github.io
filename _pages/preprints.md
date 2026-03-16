---
layout: page
title: Preprints
permalink: /preprints/
description: Preprints by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 3
---

{% include research_nav.liquid %}

<div class="research-with-sidebar">
<div class="research-sidebar-banner">
  <img src="{{ '/assets/img/teaching2.JPG' | relative_url }}" alt="Elizabeth teaching" />
</div>
<div class="research-main-content">

{% include external_profiles.liquid %}

<style>
  .preprints-bg {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    z-index: 0;
    opacity: 0.10;
    pointer-events: none;
    background: url('{{ "/assets/img/teach.PNG" | relative_url }}') center / cover no-repeat;
  }
  .preprints-content {
    position: relative;
    z-index: 1;
  }
</style>

<div class="preprints-bg"></div>

<div class="preprints-content">

<div class="publications" style="background-color: var(--global-bg-color); padding: 1.5rem 2rem; border-radius: 10px; box-shadow: 0 2px 12px rgba(0,0,0,0.08);">
{% bibliography --file preprints --sort year --order descending %}
</div>

</div>

</div><!-- .research-main-content -->
</div><!-- .research-with-sidebar -->
