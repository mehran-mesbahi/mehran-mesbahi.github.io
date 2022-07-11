---
layout: page
title: projects
permalink: /projects/
description: Selected research and project topics from past to present
nav: true
# display_categories: [work, fun]
horizontal: false
---

<strong style="color: red;">Synopsis</strong>

My research is at the intersection of control theory, networks, aerospace systems, robotics, optimization, and data science, with a multi-disciplinary twist to such areas as aerospace autonomy and dynamic networks;
see /writings/

<strong style="color: red;">Current Projects</strong>

<span style="color: orange;">NSF</span>: Autonomy of Origami-inspired Transformable Systems in Space Operations

<span style="color: orange;">NSF</span>: Data-guided Control: Fundamental Limits in Presence of Nonlinearities, Streaming Data, and Networks

<span style="color: orange;">NASA</span>: 6DOF guidance for planetary pinpoint landing

<span style="color: orange;">Blue Origin</span>: Computational guidance for rendezvous and docking

<span style="color: orange;">AFOSR</span>: Motion planning via lifting and hypercomplex geometry 

<span style="color: orange;">Boeing</span>: Robust trajectory planning in presence of obstacles and uncertain weather conditions 

<span style="color: orange;">NSF</span>: Global brain and variability 

<span style="color: orange;">JPL/NASA</span>: Robust vision-based guidance and control


<strong style="color: red;">Past Projects</strong>

<span style="color: orange;">ARO MURI</span>: Predicting and controlling systems of interdependent networks (with Raissa D'Souza)

 <span style="color: orange;">ONR</span>: Online Distributed Optimization (with Maryam Fazel)

 <span style="color: orange;">Boeing</span>: Advanced Control Methods for Aircraft Flight Systems (with Kristi Morgansen)

 <span style="color: orange;">NASA</span>: 6DOF Constrained Motion Planning Algorithms with Applications to Autonomous Pin-point Landing 

 <span style="color: orange;">DARPA</span>: Breaking the Neuro-code NSF: Data-guided decision-making for infrastructure networks


 <span style="color: orange;">DARPA</span>: Data-guided controllability: learning from the human genome (with Indika Rajapakse, Anthony Bloch, Stephen Smale)

 <span style="color: orange;">Boeing</span>: Adaptive energy management for more electric aircraft 

 <span style="color: orange;">AFOSR</span>: A Network-centric Formalism for Disturbance Rejection Design and Human-swarm Interaction

 <span style="color: orange;">NSF</span>: Semi-autonomous networks

 <span style="color: orange;">AFOSR</span>: Networked systems security: system-theoretic perspective

 <span style="color: orange;">JPL/NASA</span>: Formation observers and estimators

 <span style="color: orange;">NSF</span>: Robustness of networked systems via graph-theoretic methods

 <span style="color: orange;">Boeing</span>: Analysis and design of co-simulation frameworks

<span style="color: orange;">Boeing</span>: Multiple UAV Deconfliction 


<span style="color: orange;">NSF CAREER</span>: Distributed Space Systems


<span style="color: orange;">JPL/NASA</span>: Nonconvex Motion Planning

<span style="color: orange;">JPL/NASA</span>: Switching Control Laws for Spacecraft formations

<span style="color: orange;">Boeing</span>: UAV Formations with Switching Information-exchange topologies

<span style="color: orange;">ONR</span>: Hybrid Control for Supercavitating flight (ONR)

<span style="color: orange;">JPL/NASA</span>: Distributed estimation

<span style="color: orange;">Murdock Foundation</span>: Virtual reality for understanding complex engineering phenomena 

{% comment %}
<!-- pages/projects.md -->
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
    <div class="row row-cols-2">
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
    <div class="row row-cols-2">
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
{% endcomment %}