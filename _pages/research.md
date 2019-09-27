---
layout: archive
title: 
permalink: /research/
author_profile: true
---


{% include base_path %}

<h2> Working Papers </h2>

{% for post in site.research reversed %}
  {% include archive-single-wp.html %}
{% endfor %}


<h2> Publications </h2>

{% for post in site.publications reversed %}
  {% include archive-single-pub.html %}
{% endfor %}

<style>
  .top-ten {
     margin-top: 10cm;
  }
</style>

<p class="bottom-three">
   Order Flows and Retail Investor Impacts in Commodity Futures Markets  <ahref="http://robready.com/files/ready_ready_orderflows.pdf">Old PDF</a>
</p>


