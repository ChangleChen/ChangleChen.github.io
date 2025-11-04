---
layout: page
title: Publications
description: "Charles's research work"
permalink: /publications/
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- External Links with Icons -->
<p style="display: flex; flex-wrap: wrap; align-items: center; gap: 0.5rem;">
  <span>Up-to-date publications are also available on:</span>
  <a href="https://scholar.google.com.tw/citations?user=AuiMOtMAAAAJ&hl=en" target="_blank">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
  <a href="https://www.researchgate.net/profile/Chang-Le-Chen" target="_blank">
    <i class="ai ai-researchgate"></i> ResearchGate
  </a>

</p>

<!-- Bibsearch Feature -->
{% include bib_search.liquid %}

<div class="publications">

<!-- <h2>PhD Thesis</h2> 
# {% bibliography -f papers -q @phdthesis %}  -->

<h2>Research Articles</h2>
{% bibliography -f papers -q @article %}

<!--  <h2>Under Review</h2>
{% bibliography -f papers -q @unpublished %}

<h2>Conference Proceedings</h2>
{% bibliography -f papers -q @inproceedings %}

<h2>Presentations</h2>
{% bibliography -f papers -q @misc %}   -->

</div>
