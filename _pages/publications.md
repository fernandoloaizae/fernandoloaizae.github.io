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

* The Effects of Education on Wealth Inequality over the Life Cycle
* Life Cycle Implications of Schooling on Financial Assets
* OLG Model with Health and Long-Term Care Insurance for Inclusive Growth
* Motives for Saving in Retirement: Bequest and Long-Term Care
* Effects of the Medicaid Expansion on Formal and Informal Care Usage of Minorities
