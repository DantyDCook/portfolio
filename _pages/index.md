---
layout: default
title: Home
permalink: /
description: Evidence-backed data analytics, SQL, BI, and machine-learning portfolio for analyst and analytics engineering roles.
---

<section class="hero">
  <div>
    <p class="eyebrow">Data analyst / SQL analyst / analytics engineering portfolio</p>
    <h1>Danty Cook</h1>
    <p class="lede">I build evidence-backed analytics work: SQL transformations, Python data wrangling, BI-ready datasets, and machine-learning evaluations that make technical decisions easier to inspect.</p>
    <div class="hero-actions">
      <a class="button" href="{{ '/projects/' | relative_url }}">View projects</a>
      <a class="button-secondary" href="{{ '/resume/' | relative_url }}">View resume</a>
      <a class="button-secondary" href="https://github.com/DantyDCook" target="_blank" rel="noopener">GitHub</a>
      <a class="button-secondary" href="https://www.linkedin.com/in/dantydcook" target="_blank" rel="noopener">LinkedIn</a>
    </div>
  </div>
  <aside class="snapshot" aria-label="Professional snapshot">
    <dl>
      <dt>Role targets</dt>
      <dd>Data Analyst, BI / Reporting Analyst, SQL Analyst, Analytics Engineer, Junior Data Engineer</dd>
      <dt>Core tools evidenced</dt>
      <dd>SQL, PostgreSQL, Python, Pandas, R, scikit-learn, Tableau-ready reporting, Docker, Kafka, GitHub Actions</dd>
      <dt>Education</dt>
      <dd>B.S. Data Analytics, Western Governors University. A.A. Business Administration / Information Systems.</dd>
      <dt>Certifications</dt>
      <dd>CompTIA Data+, A+, Network+, Project+, CIOS, ITIL v4</dd>
    </dl>
  </aside>
</section>

<section class="section">
  <div class="section-head">
    <div>
      <p class="eyebrow">Featured evidence</p>
      <h2>Projects that show the work</h2>
    </div>
    <a href="{{ '/projects/' | relative_url }}">All projects</a>
  </div>
  <div class="project-grid">
    {% assign featured_projects = site.projects | where_exp: "p", "p.featured == true" | sort: "priority" %}
    {% for p in featured_projects limit: 5 %}
      {% include project-card.html project=p %}
    {% endfor %}
  </div>
</section>

<section class="section">
  <p class="eyebrow">Capability model</p>
  <h2>What the portfolio is organized to prove</h2>
  <div class="capability-grid">
    <div class="card"><h3>Data & SQL</h3><p>PostgreSQL workflows, staged transformations, functions, procedures, CTEs, joins, and reporting tables.</p></div>
    <div class="card"><h3>Analytics</h3><p>Python/R data cleaning, exploratory analysis, statistical review, visual outputs, and data-quality checks.</p></div>
    <div class="card"><h3>BI & Reporting</h3><p>Dashboard-ready datasets, KPI-oriented summaries, Tableau-style visuals, and reusable reporting artifacts.</p></div>
    <div class="card"><h3>Machine Learning</h3><p>Supervised and unsupervised model evaluation, PCA, clustering, classification, and anomaly-detection tradeoff analysis.</p></div>
  </div>
</section>

<section class="section">
  <p class="eyebrow">Professional context</p>
  <h2>Operational background plus data systems training</h2>
  <p class="lede">My background combines technical support, documentation, reporting, medical transcription, property operations, and formal data analytics training. The site now leads with implementation evidence and keeps academic provenance visible as context.</p>
  <div class="button-row">
    <a class="button" href="mailto:hireme@dantydcook.com">Contact me</a>
    <a class="button-secondary" href="{{ '/about/' | relative_url }}">About</a>
  </div>
</section>
