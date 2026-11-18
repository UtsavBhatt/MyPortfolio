---
title: "Selected work"
permalink: /projects/
layout: single
author_profile: false
classes: wide portfolio-page
---

<p class="eyebrow">PROJECT INDEX</p>

# Selected work

Research, datasets and financial models. Each project is presented with its question, approach and inspectable output. Work in progress is labelled as such.

<div class="project-list project-list-page">
  {% for project in site.data.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</div>

<p class="project-note">Project status is stated openly. A project marked “In progress” is not presented as a completed deliverable.</p>
