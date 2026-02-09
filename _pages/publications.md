---
layout: default
title: Publications
permalink: /publications/
description: Publications by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

<div class="publications">
{% bibliography --file papers --sort year --order descending %}
</div>
