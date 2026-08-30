---
layout: default
title: Projects
permalink: /projects/
description: Evidence-backed data analytics, SQL, BI, and machine-learning projects by Danty Cook.
---

<header class="page-hero">
  <p class="eyebrow">Project library</p>
  <h1>Evidence-backed technical projects</h1>
  <p class="lede">Course numbers are preserved as context, but each project is framed around the professional capability it demonstrates: data transformation, reporting, modeling, validation, and communication.</p>
</header>

<section class="section">
  <h2>Featured</h2>
  <div class="project-grid">
    {% assign featured_projects = site.projects | where_exp: "p", "p.featured == true" | sort: "priority" %}
    {% for p in featured_projects %}
      {% include project-card.html project=p %}
    {% endfor %}
  </div>
</section>

<section class="section">
  <h2>Supporting Library</h2>
  <div class="project-grid">
    {% assign supporting_projects = site.projects | where_exp: "p", "p.published != false and p.featured != true" | sort: "priority" %}
    {% for p in supporting_projects %}
      {% include project-card.html project=p %}
    {% endfor %}
  </div>
</section>
