---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

<h2 class="bibliography">Work in Progress</h2>

{% bibliography --query @article[journal=preprint] --group_by none %}

{% bibliography --query @inproceedings %}

</div>
