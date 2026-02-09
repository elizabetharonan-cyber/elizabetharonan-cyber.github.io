---
layout: page
permalink: /publications/
title: Research Articles
description: Publications by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: true
nav_order: 2
---

<!-- Search box for publications -->
{% include bib_search.liquid %}

<div class="publications">

{% bibliography --file papers --sort year --order descending --heading "Research Articles" %}

</div>
