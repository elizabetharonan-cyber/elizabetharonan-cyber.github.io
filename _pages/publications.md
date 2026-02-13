---
layout: default
title: Publications
permalink: /publications/
description: Publications by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: true
nav_order: 2
---

<div style="margin-bottom: 2rem; padding: 1rem; background-color: var(--global-bg-color); border-left: 3px solid var(--global-theme-color);">
  <strong>Publication Types:</strong>
  <a href="/publications/" style="margin-left: 1rem;">Research Articles</a> |
  <a href="/preprints/" style="margin-left: 0.5rem;">Preprints</a> |
  <a href="/reviews/" style="margin-left: 0.5rem;">Reviews & Commentaries</a> |
  <a href="/protocols/" style="margin-left: 0.5rem;">Protocols</a>
</div>

<div style="display: flex; gap: 2rem; align-items: flex-start;">
  <!-- Left Sidebar -->
  <div style="flex-shrink: 0; width: 200px;">
    <div style="padding: 1.5rem; background-color: var(--global-bg-color); border: 1px solid var(--global-divider-color); border-radius: 6px;">
      <h4 style="margin-top: 0; margin-bottom: 1rem; font-size: 1rem;">External Profiles</h4>
      <ul style="list-style: none; padding: 0; margin: 0;">
        <li style="margin-bottom: 0.75rem;">
          <a href="https://www.ncbi.nlm.nih.gov/myncbi/1niJzd-Lz-oAF/bibliography/public/" target="_blank" rel="noopener noreferrer" style="display: flex; align-items: center; text-decoration: none;">
            <i class="ai ai-pubmed" style="font-size: 1.5rem; margin-right: 0.5rem;"></i>
            NCBI Bibliography
          </a>
        </li>
        <li style="margin-bottom: 0.75rem;">
          <a href="https://scholar.google.com/citations?hl=en&user=8YQwM9IAAAAJ" target="_blank" rel="noopener noreferrer" style="display: flex; align-items: center; text-decoration: none;">
            <i class="ai ai-google-scholar" style="font-size: 1.5rem; margin-right: 0.5rem;"></i>
            Google Scholar
          </a>
        </li>
        <li>
          <a href="https://orcid.org/0000-0001-7400-5718" target="_blank" rel="noopener noreferrer" style="display: flex; align-items: center; text-decoration: none;">
            <i class="ai ai-orcid" style="font-size: 1.5rem; margin-right: 0.5rem;"></i>
            ORCID
          </a>
        </li>
      </ul>
    </div>
  </div>

  <!-- Main Content -->
  <div style="flex: 1; min-width: 0;">
    {% include bib_search.liquid %}

    <div class="publications">
    {% bibliography --file papers --sort year --order descending %}
    </div>

  </div>
</div>
