---
layout: page_milo
title: MILO-Group
permalink: /milo-group/
description: >
nav: true
nav_order: 4
display_categories: [Projects, Master Students, Undergraduate Students]
horizontal: true
profile:
  align: right
  image: milo-group.png
  image_circular: true # crops the image to make it circular
  address: >
---

<h6> Founded in 2022, Led by <a href="https://midasdming.github.io">Dr. Di Ming</a>. </h6>

<h6> At MILO group, we have broad research interests spanning from the theory to the application aspects of machine learning and large-scale optimization. Our current research works include: sparse learning, network pruning, adversarial attack, semantic segmentation, graph learning, clustering, self-supervised learning, nonlinear optimization, bilevel optimization, curriculum optimization, multi-stage optimization, etc. </h6>

<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-1">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
</div>
