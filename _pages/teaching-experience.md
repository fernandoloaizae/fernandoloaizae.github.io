---
layout: archive
title: "Teaching"
permalink: /teaching-experience/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}



### T.A. Finance and Growth<span class="year">2020-2023</span>

<div class="details">
  M.Sc. Economia dei Mercati e degli Intermediari Finanziari, University of Rome Tor Vergata
</div>

<div class="syllabus-container">
  <span class="syllabus-toggle" onclick="toggleSyllabus('TA1-syllabus')">
    <span class="triangle">&#9654;</span> Syllabus
  </span>
  <div id="TA1-syllabus" style="display:none; margin-top: 8px;">
    <ul>
      <li>Economic growth models</li>
      <li>Financial development and economic growth</li>
      <li>Financial markets, growth, and income distribution</li>
      <li>Institutions and unified growth theory</li>
      <li>Empirical analysis of economic growth</li>
    </ul>
  </div>
</div>


### T.A. Business Statistics in R<span class="year">2018-2019</span>

<div class="details">
  M.Sc. European Economy and Business Law, University of Rome Tor Vergata
</div>

<div class="syllabus-container">
  <span class="syllabus-toggle" onclick="toggleSyllabus('TA2-syllabus')">
    <span class="triangle">&#9654;</span> Syllabus
  </span>
  <div id="TA2-syllabus" style="display:none; margin-top: 8px;">
    <ul>
      <li>Linear regression, model evaluation, principal component analysis</li>
      <li>Lasso, ridge regression, logistic regression</li>
      <li>Smoothing, splines, kernel smoothing, local polynomial</li>
      <li>Nearest neighbors, naive Bayes, additive models, regression trees</li>
    </ul>
  </div>
</div>


### T.A. Mathematics 1<span class="year">2019</span>

<div class="details">
  B.Sc. Business Administration and Economics, University of Rome Tor Vergat
</div>

<div class="syllabus-container">
  <span class="syllabus-toggle" onclick="toggleSyllabus('TA3-syllabus')">
    <span class="triangle">&#9654;</span> Syllabus
  </span>
  <div id="TA3-syllabus" style="display:none; margin-top: 8px;">
    <ul>
      <li>Topology</li>
      <li>Calculus</li>
      <li>Linear Algebra</li>
      <li>Optimization</li>
    </ul>
  </div>
</div>

### Primary School Teacher<span class="year">206</span>

<div class="details">
  Unidad Educativa San Jose La Salle
</div>


<style>
.year {
  font-weight: normal;
  font-size: 0.9em;
  margin-left: 10px;
}

.details {
  font-weight: normal;
  font-size: 0.9em;
  margin-left: 10px;
  margin-bottom: 5px;
}

.syllabus-container {
  margin-top: 0.2em;
  margin-bottom: 5px;
}

.syllabus-toggle {
  cursor: pointer;
  color: #333;
  display: inline-flex;
  align-items: center;
  font-size: 0.9em;
}

.triangle {
  margin-right: 5px;
  transition: transform 0.3s ease;
}

#jmp-syllabus {
  margin-top: 8px;
}
</style>

<script>
  function toggleSyllabus(id) {
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
