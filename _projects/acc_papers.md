---
layout: page
title: Papers, reviews, tutorials
description: 
img: #assets/img/3.jpg
importance: 2
category: Accelerating bioinformatics
years: [2020]
nav: true
nav_order: 5
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f acc_papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
