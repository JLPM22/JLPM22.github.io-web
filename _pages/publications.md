---
layout: page
permalink: /publications/
title: publications
years: [2024, 2023, 2022]
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
