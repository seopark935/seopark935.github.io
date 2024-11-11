---
layout: page
title: notes
permalink: /notes/
description: Notes covering Georgia Tech's dual enrollment courses (2022 - 2024) and current ECE courses. These notes are not comprehensive, so keep that in mind if you (or others) are using them to study. As always, lecture videos and textbook chapters will always be more informative. Please attribute if you are planning to compile these into study materials.
nav: true
nav_order: 3
display_categories: [math, ece]
horizontal: false
---

<!-- pages/notes.md -->
<div class="notes">
{% if site.enable_notes_categories and page.display_categories %}
  <!-- Display categorized notes -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_notes = site.notes | where: "category", category %}
  {% assign sorted_notes = categorized_notes | sort: "importance" %}
  <!-- Generate cards for each notes -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for notes in sorted_notes %}
      {% include notes_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for notes in sorted_notes %}
      {% include notes.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display notes without categories -->

{% assign sorted_notes = site.notes | sort: "importance" %}

  <!-- Generate cards for each notes -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for notes in sorted_notes %}
      {% include notes_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for notes in sorted_notes %}
      {% include notes.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>