---
layout: page
permalink: /publications/
title: publications
description: For full list, visit my <a href="https://scholar.google.com/citations?user=84Cbsz0AAAAJ&hl=en" class="custom">scholar page</a> 
categories: [Working papers, Refereed, Lightly refereed]
nav: true
---

<div class="publications">

{% for cat in page.categories %}
	<h1 class="cat">{{cat}}</h1>
	{% bibliography -f papers -q @*[category={{cat}}]* %}
{% endfor %}

</div>
