---
layout: page
permalink: /publications/
title: publications
description: For more up to date information, please visit my <a href='https://scholar.google.com/citations?user=oMzSCbMAAAAJ&hl=en'> Google Scholar</a> page. 
years: [2023, 2022, 2020, 2019, 2018, 2016]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
