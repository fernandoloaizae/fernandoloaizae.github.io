---
layout: archive
title: "Blog"
permalink: /posts/
author_profile: true
entries_layout: grid     # 2-column cards
show_excerpts: true      # show short summaries
---

{% include base_path %}

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
