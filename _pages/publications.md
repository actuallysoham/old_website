---
layout: page
permalink: /research/
title: research
description: List of published and ongoing studies (* indicates equal contributions)
years: [2022]
type: [ongoing, published, media]
nav: true
display_categories: [themes]
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

  I'm currently interested in mitigating online harms (such as misinformation, polarisation) by carefully leveraging state-of-the-art language models (LLMs). In parallel, I'm also keen to understand the broader impact of LLMs on online spaces - and what we can do towards bulding a better future.  <br/><br/>

  Much of my past research deals with strategic information operations and political influencing in the Global South. This includes studies on rumours, conspiracies and other forms of online influencing, primarily on X (formerly, Twitter).

{%- for y in page.type %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[metatype={{y}}]* %}
{% endfor %}

</div>