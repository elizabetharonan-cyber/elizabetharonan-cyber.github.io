---
layout: default
title: Protocols
permalink: /protocols/
description: Protocols by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: true
nav_order: 5
---

{% include bib_search.liquid %}

<div class="d-flex align-items-start">
	<img src="/assets/img/SoundMethods_Cover.jpg" alt="Biophysics Report Cover Story" style="width: 240px; height: auto; margin-right: 1rem;" />
	<div class="w-100">
<div class="publications">
{% bibliography --file protocols --sort year --order descending %}
</div>
	</div>
</div>
