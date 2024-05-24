---
layout: page
permalink: /publications/
title: Publications
description:
biopimyears: [2024, 2023]
years: [2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
nav_order: 5
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.biopimyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

<h1>Posters</h1>

<div class="publications">
{%- for y in page.biopimyears %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f posters -q @*[year={{y}}]* %}
{% endfor %}

</div>

<h1>Related Publications</h1>

<div class="publications">
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f related -q @*[year={{y}}]* %}
{% endfor %}

</div>
