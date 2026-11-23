---
title: Projects
nav:
  order: 2
  tooltip: Research projects
---

# {% include icon.html icon="fa-solid fa-flask" %}Projects

{% include section.html %}

## Projects I lead

{% include list.html component="card" data="projects" filter="group == 'lead'" %}

{% include section.html %}

## Projects I take part in

{% include list.html component="card" data="projects" filter="group == 'participant'" %}
