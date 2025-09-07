---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Peer-Reviewed Publications</h2>
{% bibliography --query @article,@inproceedings,@phdthesis %}

<hr>

<h2>Working Papers</h2>
{% bibliography --query @unpublished %}
</div>
