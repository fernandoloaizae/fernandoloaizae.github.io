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

<span class="abstract-toggle" onclick="toggleAbstract('jmp-abstract')">
  <span class="triangle">&#9654;</span> Abstract
</span> 
<span class="separator">|</span> 
<a href="https://fernandoloaizae.github.io/files/Loaiza_JMP23.pdf" class="download-link">Download Job Market Paper</a>
<div id="jmp-abstract" style="display:none; margin-top: 10px;">
This study investigates the causal relationship between education and wealth accumulation. Utilizing three distinct identification strategies, the research analyzes a panel dataset from the United States, encompassing two generations, to explore the dynamics of this relationship. The empirical findings indicate that higher educational attainment, particularly at the college and postgraduate levels, leads to a significant increase in lifetime wealth. This effect varies based on an individual's life stage, their position within the wealth distribution, and the level of education attained. Subsequently, the paper develops a life-cycle heterogeneous agents model to assess the impact of educational policies on wealth accumulation. Calibrated using U.S. data, this model focuses on policies aimed at enhancing the quality and quantity of higher education. The analysis reveals that increasing the proportion of college-educated individuals could potentially reduce wealth inequality. This study contributes to the understanding of education as a relevant factor in wealth generation and distribution.
</div>



## Working Papers

{% for post in site.publications reversed %}
  {% include archive-new-single.html %}
{% endfor %}

## Research in Progress


Macroeconomic Implications of the Care Wave 

<span class="abstract-toggle" onclick="toggleAbstract('bbf-abstract')">
  <span class="triangle">&#9654;</span> Abstract
</span> 
<span class="separator">|</span> 
<a href="https://fernandoloaizae.github.io/files/WP6_Deliverable.pdf" class="download-link">PDF</a>
<div id="bbf-abstract" style="display:none; margin-top: 10px;">
This document describes the construction of an overlapping generations (OLG) model that projects the macroeconomic implications of the major demographic changes happening in Europe in the 21st century, with a focus on two key trends: the retirement of the 'baby boomer' generation and the increasing need for long-term care (LTC). As the 'baby boomers' retire, significant changes are happening in European societies, especially in how pensions are handled and the growing demand for LTC. This research examines the economic and social effects of these changes, putting a spotlight on how an aging population interacts with labor supply and social inequalities. The model includes features such as heterogeneity of health and the resulting provision of care. The hypotheses this research investigates are that these demographic changes, especially the rising need for LTC, will slow down economic growth in Europe and that the increasing cost of LTC will hit lowerincome families harder, making social inequalities worse, and affecting the labor supply of women. By using a detailed OLG model that will be calibrated to represent continental Europe, we aim to show the trade-offs between financial stability, social welfare, and fairness across generations in the face of Europe's changing demographics. The model’s results are meant to help policymakers find a balance between meeting the needs of an aging population and maintaining the overall economic and social health of European societies. 
</div>



<style>
.abstract-toggle {
  cursor: pointer;
  color: #333;
  font-weight: bold;
  display: inline-flex;
  align-items: center;
}

.triangle {
  margin-right: 5px;
  transition: transform 0.3s ease;
}

#jmp-abstract[open] .triangle {
  transform: rotate(90deg);
}

.separator {
  margin: 0 10px;
  color: #ccc;
}

.download-link {
  color: #1e90ff;
  text-decoration: none;
}

.download-link:hover {
  text-decoration: underline;
}
</style>

<script>
  function toggleAbstract(id) {
    var element = document.getElementById(id);
    var triangle = element.previousElementSibling.querySelector('.triangle');
    if (element.style.display === "none") {
      element.style.display = "block";
      triangle.style.transform = "rotate(90deg)";
    } else {
      element.style.display = "none";
      triangle.style.transform = "rotate(0deg)";
    }
  }
</script>
