---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">


<h1 class="bibliography">Preprints</h1>

{% bibliography -f {{ site.scholar.bibliography }} -q @unpublished %}

<h1 class="bibliography">Journal papers</h1>

{% bibliography -f {{ site.scholar.bibliography }} -q @article %}

<h1 class="bibliography">Theses</h1>

{% bibliography -f {{ site.scholar.bibliography }} -q @thesis %}

</div>
