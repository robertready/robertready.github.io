---
layout: archive
title: 
permalink: /research/
author_profile: true
---


{% include base_path %}

<h1> Working Papers </h1>

{% for post in site.research reversed %}
  {% include archive-single-wp.html %}
{% endfor %}


<h1> Publications </h1>

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}


