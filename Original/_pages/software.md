---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

Stata for chapter 1 https://github.com/fernandoloaizae/Life_cycle/rouwenhorst.py

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
