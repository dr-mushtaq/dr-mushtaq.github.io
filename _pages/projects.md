---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="container">
    <h1>Academic Details</h1>
    <div class="service">
        {% assign projects = site.data.projects %}
        {% for project in projects %}
        <div class="service-item">
            <center><img src="{{ project.image }}" alt="{{ project.title }}" /></center>
            <div class="service-content">
                <div class="service-title">{{ project.title }}</div>
                <div class="service-description">Major: {{ project.major }}</div>
                <p>Supervisors: {{ project.supervisor }}</p>
                <p>Dates: {{ project.dates }}</p>
                <p>{{ project.institution }}</p>
            </div>
        </div>
        {% endfor %}
    </div>
</div>
