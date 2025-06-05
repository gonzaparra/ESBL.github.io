---
title: "Resources"
layout: default
permalink: /resources/
---

<h2>Resources</h2>

<ul style="list-style: none; padding: 0;">
  {% for resource in site.data.resources %}
    <li style="margin-bottom: 20px;">
      <a href="{{ resource.link }}" target="_blank" style="text-decoration: none; display: flex; align-items: center;">
        {% if resource.image %}
          <img src="{{ '/assets/img/' | append: resource.image }}" alt="{{ resource.title }}" style="height: 50px; margin-right: 15px;" />
        {% endif %}
        <span style="font-size: 1.2em;">{{ resource.title }}</span>
      </a>
    </li>
  {% endfor %}
</ul>
