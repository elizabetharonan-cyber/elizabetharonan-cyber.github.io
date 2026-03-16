---
layout: page
title: Reviews & Commentaries
permalink: /reviews/
description: Reviews and commentaries by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: false
nav_order: 4
---

{% include research_nav.liquid %}

<div class="research-with-sidebar">
<div class="research-sidebar-banner">
  <img src="{{ '/assets/img/teaching2.JPG' | relative_url }}" alt="Elizabeth teaching" />
</div>
<div class="research-main-content">

{% include external_profiles.liquid %}

<div class="publications reviews-page">
{% bibliography --file reviews --sort year --order descending %}
</div>

</div><!-- .research-main-content -->
</div><!-- .research-with-sidebar -->
