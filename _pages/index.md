---
layout: page
title: Home
permalink: /
nav: false
---

<div style="text-align: center; padding: 3rem 0;">
  <img src="/assets/img/liz_lab1.jpg" alt="Elizabeth A. Ronan" style="width: 250px; height: 250px; border-radius: 50%; object-fit: cover; margin-bottom: 2rem;" />
  
  <h1>Elizabeth A. Ronan, PhD</h1>
  <h3 style="color: var(--global-text-color-light); font-weight: 400;">Postdoctoral Researcher</h3>
  <p style="color: var(--global-text-color-light);">University of Michigan School of Dentistry</p>
  
  <div style="margin: 3rem 0;">
    <p style="font-size: 1.2rem; max-width: 800px; margin: 0 auto; line-height: 1.8;">
      Welcome! I am a neuroscientist studying the molecular and cellular mechanisms of orofacial somatosensation and pain. 
      My research integrates insights from both invertebrate and vertebrate model systems to understand how sensory neurons 
      detect, encode, and transmit information that drives perception, behavior, and homeostasis.
    </p>
  </div>
  
  <div style="margin: 2rem 0;">
    <a href="/about/" class="btn btn-primary" style="margin: 0.5rem;">Learn More About Me</a>
    <a href="/publications/" class="btn btn-outline-primary" style="margin: 0.5rem;">View Publications</a>
    <a href="/contact/" class="btn btn-outline-primary" style="margin: 0.5rem;">Contact Me</a>
  </div>
</div>

<hr style="margin: 4rem 0;" />

<div style="max-width: 900px; margin: 0 auto;">
  <h2 style="text-align: center; margin-bottom: 2rem;">Recent Highlights</h2>
  
  {% if site.announcements.enabled %}
  <div class="news">
    {% include news.liquid limit=3 %}
  </div>
  {% endif %}
</div>
