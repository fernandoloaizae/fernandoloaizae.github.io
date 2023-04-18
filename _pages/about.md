---
layout: page
title: 
---


I try to understand the economic inequality.

I am based at the [Max Planck Institute for Social Law and Social Policy](https://www.bto.org/) where I work as an Postdoctoral Researcher. 

Prior to my current job I was a Ph.D. researcher in the [Department of Economics](http://www.sadieryan.net/) at the niversity of Rome Tor Vergata.



<h3> Recent News and Blog posts  </h3>

<div class="post-titles">
  {% for post in site.posts limit: 5 %}
   <div class="post-title">
   {{ post.date | date_to_string }}:   <a href="{{ post.url }}">{{ post.title }}</a>
  </div>
  {% endfor %}
</div>
