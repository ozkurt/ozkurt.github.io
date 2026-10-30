---
layout: page
permalink: /publications/
title: publications
description: Full list of publications in reverse chronological order. * Equal contribution. See also my <a href="https://scholar.google.com/citations?user=VyalptsAAAAJ">Google Scholar</a> profile.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Makes my name bold (the theme already underlines it) -->
<style>
  .publications .author > em { font-weight: 700; }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
