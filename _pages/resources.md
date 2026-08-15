---
layout: page
title: Resources
permalink: /resources/
description: Fee waivers, funding, applications, and free learning resources.
nav: false
_styles: >
  .resource-card {
    display: flex;
    flex-direction: column;
    height: 100%;
    padding: 1.5rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background-color: var(--global-card-bg-color);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .resource-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.1);
  }
  .resource-card h3 {
    margin-top: 0;
    margin-bottom: 0.25rem;
    font-size: 1.35rem;
  }
  .resource-card h3 a {
    color: var(--global-theme-color);
  }
  .resource-card .card-who {
    font-size: 0.85rem;
    text-transform: uppercase;
    letter-spacing: 0.06em;
    color: var(--global-text-color-light);
    margin-bottom: 0.75rem;
  }
  .resource-card ul {
    padding-left: 1.1rem;
    margin-bottom: 1.25rem;
  }
  .resource-card ul li {
    margin-bottom: 0.35rem;
    font-size: 0.95rem;
  }
  .resource-card .card-cta {
    margin-top: auto;
  }
  .resource-card .card-cta a {
    display: inline-block;
    padding: 0.4rem 1rem;
    border: 1px solid var(--global-theme-color);
    border-radius: 5px;
    color: var(--global-theme-color);
    font-size: 0.9rem;
  }
  .resource-card .card-cta a:hover {
    background-color: var(--global-theme-color);
    color: var(--global-bg-color);
    text-decoration: none;
  }
  .resource-grid {
    margin-top: 1.5rem;
    margin-bottom: 2rem;
  }
  .resource-grid > div {
    margin-bottom: 1.5rem;
  }
---

<p>
  Notes on fee waivers, funding, applications, and free learning resources, collected from my own path through college and graduate school in astrophysics.
</p>

<div class="row resource-grid">
  <div class="col-md-6">
    <div class="resource-card">
      <h3><a href="{{ '/resources/hs/' | relative_url }}">High School</a></h3>
      <div class="card-who">Applying to college</div>
      <p>Applying to and paying for undergrad, plus science opportunities beforehand.</p>
      <ul>
        <li><strong>Application fee waivers</strong> — eligibility and how to request one</li>
        <li><strong>QuestBridge</strong> — National College Match and College Prep Scholars</li>
        <li><strong>Scholarships</strong> — New York State and national</li>
        <li><strong>Fly-in programs</strong> — free campus visits</li>
        <li><strong>Summer research</strong> — free and stipended STEM programs</li>
        <li><strong>Free learning</strong> — textbooks, courses, coding, astronomy</li>
        <li><strong>Competitions</strong> — olympiads and science fairs</li>
      </ul>
      <div class="card-cta">
        <a href="{{ '/resources/hs/' | relative_url }}">Open High School resources →</a>
      </div>
    </div>
  </div>

  <div class="col-md-6">
    <div class="resource-card">
      <h3><a href="{{ '/resources/he/' | relative_url }}">Higher Education</a></h3>
      <div class="card-who">In college or applying to grad school</div>
      <p>Graduate school applications, funding, and research.</p>
      <ul>
        <li><strong>Grad application fee waivers</strong> — four routes to one</li>
        <li><strong>Preview &amp; pre-application programs</strong> — funded campus visits</li>
        <li><strong>Bridge programs</strong> — APS, Cal-Bridge, Fisk–Vanderbilt</li>
        <li><strong>GRE &amp; program requirements</strong> — including a spreadsheet of current policies</li>
        <li><strong>Reading on grad school</strong> — guides and first-hand accounts</li>
        <li><strong>Fellowships</strong> — undergraduate and graduate</li>
        <li><strong>Research &amp; societies</strong> — REUs, tools, professional organizations</li>
      </ul>
      <div class="card-cta">
        <a href="{{ '/resources/he/' | relative_url }}">Open Higher Education resources →</a>
      </div>
    </div>
  </div>
</div>

<hr>

<p>
  Deadlines and eligibility change yearly. Confirm details on each program's own site. If something is out of date or worth adding, <a href="{{ '/contact/' | relative_url }}">let me know</a>.
</p>
