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

## Job Market Paper

### The Effects of Education on Wealth Inequality over the Life Cycle

**Abstract:** This study investigates the causal relationship between education and wealth accumulation. Utilizing three distinct identification strategies, the research analyzes a panel dataset from the United States, encompassing two generations, to explore the dynamics of this relationship. The empirical findings indicate that higher educational attainment, particularly at the college and postgraduate levels, leads to a significant increase in lifetime wealth. This effect varies based on an individual's life stage, their position within the wealth distribution, and the level of education attained. Subsequently, the paper develops a life-cycle heterogeneous agents model to assess the impact of educational policies on wealth accumulation. Calibrated using U.S. data, this model focuses on policies aimed at enhancing the quality and quantity of higher education. The analysis reveals that increasing the proportion of college-educated individuals could potentially reduce wealth inequality. This study contributes to the understanding of education as a relevant factor in wealth generation and distribution.

[Download Job Market Paper here](https://fernandoloaizae.github.io/files/Loaiza_JMP23.pdf)


## Working Papers

{% for post in site.publications reversed %}
  {% include archive-new-single.html %}
{% endfor %}

## Research in Progress


Macroeconomic Implications of the Care Wave [(PDF)](https://fernandoloaizae.github.io/files/WP6_Deliverable.pdf)
