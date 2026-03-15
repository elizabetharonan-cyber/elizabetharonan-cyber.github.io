---
layout: page
title:
permalink: /
nav: false
---

<div style="display: flex; gap: 3rem; align-items: center; padding: 0; flex-wrap: wrap;">
  <!-- Image -->
  <div style="flex-shrink: 0;">
    <img src="/assets/img/liz_lab1.jpg" alt="Elizabeth A. Ronan" style="width: 400px; max-width: 100%; height: auto; border-radius: 8px;" />
  </div>
  
  <!-- Content -->
  <div style="flex: 1; min-width: 300px;">
    <h1 style="margin-top: 0;">Elizabeth A. Ronan, PhD</h1>
    <h3 style="color: var(--global-text-color-light); font-weight: 400; margin-top: 0.5rem;">Postdoctoral Researcher</h3>
    <p style="color: var(--global-text-color-light); margin-bottom: 2rem;">University of Michigan School of Dentistry</p>
    
    <p style="font-size: 1.1rem; line-height: 1.8; margin-bottom: 1.5rem;">
      Welcome! I am a neuroscientist studying the molecular and cellular mechanisms of orofacial somatosensation and pain. 
      My research integrates insights from both invertebrate and vertebrate model systems to understand how sensory neurons 
      detect, encode, and transmit information that drives perception, behavior, and homeostasis.
    </p>
    
    <!-- Social Links -->
    <div style="margin-bottom: 2rem; display: flex; gap: 1rem; flex-wrap: wrap; font-size: 1.5rem;">
      <a href="mailto:elizabeth.a.ronan@gmail.com" title="Email"><i class="fa-solid fa-envelope"></i></a>
      <a href="https://bsky.app/profile/elizabithian.bsky.social" target="_blank" rel="noopener noreferrer" title="Bluesky"><i class="fa-brands fa-bluesky"></i></a>
      <a href="https://www.linkedin.com/in/lizronan/" target="_blank" rel="noopener noreferrer" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a>
      <a href="https://orcid.org/0000-0001-7400-5718" target="_blank" rel="noopener noreferrer" title="ORCID"><i class="ai ai-orcid"></i></a>
      <a href="https://scholar.google.com/citations?user=8YQwM9IAAAAJ" target="_blank" rel="noopener noreferrer" title="Google Scholar"><i class="ai ai-google-scholar"></i></a>
      <a href="https://x.com/elizabithian" target="_blank" rel="noopener noreferrer" title="Twitter/X"><i class="fa-brands fa-x-twitter"></i></a>
    </div>
    
    <div style="display: flex; gap: 0.75rem; flex-wrap: wrap;">
      <a href="/about/" class="btn btn-primary">Learn More About Me</a>
      <a href="/publications/" class="btn btn-outline-primary">View Publications</a>
      <a href="/contact/" class="btn btn-outline-primary">Contact Me</a>
    </div>
  </div>
</div>

<hr style="margin: 4rem 0;" />

<!-- Recent Highlights -->
<div style="max-width: 900px; margin: 0 auto; margin-bottom: 3rem;">
  <h2 style="text-align: center; margin-bottom: 2rem;">Recent Highlights</h2>
  <div class="news">
    {% include news.liquid limit=5 %}
  </div>
</div>

<!-- Selected Publications -->
<div class="selected-papers" style="max-width: 900px; margin: 0 auto; margin-bottom: 3rem;">
  <h2 style="text-align: center; margin-bottom: 2rem;">Selected Publications</h2>
  {% include selected_papers.liquid %}
</div>

<!-- Latest Blog Posts -->
<div style="max-width: 900px; margin: 0 auto;">
  <h2 style="text-align: center; margin-bottom: 2rem;">Latest Posts</h2>
  {% include latest_posts.liquid %}
</div>
