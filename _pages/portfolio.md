---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

My recent work combines scientific information extraction with practical machine learning applications. Each project page explains the goal, approach, and current outcome.

{% assign projects = site.portfolio | sort: "order" %}

## Recent research and applied work

<div class="portfolio-grid">
{% for post in projects %}
  {% if post.order < 4 %}
    {% include portfolio-card.html post=post %}
  {% endif %}
{% endfor %}
</div>

## Earlier projects

<div class="portfolio-grid">
{% for post in projects %}
  {% if post.order >= 4 %}
    {% include portfolio-card.html post=post %}
  {% endif %}
{% endfor %}
</div>

