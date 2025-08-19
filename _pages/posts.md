---
layout: archive
title: "Blog"
permalink: /posts/
author_profile: true
entries_layout: grid     # two-column “cards”
show_excerpts: true      # show short summaries
classes: page--blog      # custom class so we can style just this page
---

{% include base_path %}

{% for post in site.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include paginator.html %}
