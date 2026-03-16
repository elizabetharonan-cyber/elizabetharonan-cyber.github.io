---
layout: page
title: Preprints
permalink: /preprints/
description: Preprints by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 3
---

{% include research_nav.liquid %}

<style>
  .preprints-bg {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    z-index: 0;
    opacity: 0.15;
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

<div class="publications">
{% bibliography --file preprints --sort year --order descending %}
</div>

</div>
