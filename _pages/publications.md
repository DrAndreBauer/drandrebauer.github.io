---
layout: page
permalink: /publications/
title: Publications
description: All publications are in reversed chronological order.
nav: true
nav_order: 3
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017]
showbib: true
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{%- for y in page.years %}
  <h2 class="year bibliography">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
