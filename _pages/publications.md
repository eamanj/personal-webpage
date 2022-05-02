---
layout: page
permalink: /publications/
title: Publications
description: For full list, visit my <a href='https://scholar.google.com/citations?user=84Cbsz0AAAAJ&hl=en' class='custom'>scholar page</a> 
categories: [Working papers, Refereed, Lightly refereed]
nav: true
---
<div class="publications">

{% for cat in page.categories %}
	<h1 class="cat">{{cat}}</h1>
	{% bibliography -f papers -q @*[category={{cat}}]* %}
{% endfor %}

</div>

<!--
years: [1956, 1950, 1935, 1905] # put this above in config
For ordering of papers by year.
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
-->
