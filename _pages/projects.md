---
layout: default
title: Timothy Duffy - Portfolio
permalink: /projects/
---

## Fluid-Mechanical Dissection

I’ll use this page to document my fluid-mechanical dissection.

[View the dissection page]({{ "/fluid-mechanical-dissection/" | relative_url }})

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
