---
layout: news-list
title: lectures
permalink: /lectures/
description: Open course materials and lecture notes from our group.
nav: true
nav_order: 6
---

# Lectures

<!-- pages/lectures.md -->
<div class="projects">
{% assign sorted_lectures = site.lectures | sort: "importance" %}

  <!-- Generate cards for each lecture -->
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_lectures %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
