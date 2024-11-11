---
layout: page
title: notes
permalink: /notes/
description: A growing collection of your cool notes.
nav: true
nav_order: 2
display_categories: [competition, club]
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