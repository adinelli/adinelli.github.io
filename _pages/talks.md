---
layout: page
permalink: /talks/
title: Talks
description:
years: [2025,2024,2023,2022,2021]
type: [Invited talks,Contributed talks,Seminars,Flash talks]
nav: true
nav_order: 1
---
<!-- _pages/talks.md -->
<div class="talks">

{%- for y in page.type %}
  <h2 class="type">{{y}}</h2>
  {% bibliography -f talks -q @*[type={{y}}]* %}
{% endfor %}

</div>
