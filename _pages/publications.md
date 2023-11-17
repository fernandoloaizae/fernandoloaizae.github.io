---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Working Papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Current Research

* Life Cycle Implications of Schooling on Financial Assets
* Macroeconomic Implications of the Care Wave (with Börsch-Supan, A.)
