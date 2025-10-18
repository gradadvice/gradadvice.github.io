---
layout: page
title: Resources
permalink: /resources/
---

# Resources Directory

A curated collection of helpful resources for PhD students, including tools, websites, books, and other materials.

## Available Resources

{% for resource in site.resources %}
- [{{ resource.title }}]({{ resource.url | relative_url }})
  {{ resource.excerpt }}
{% endfor %}

---

## Categories

Resources are organized by category to help you find what you need:
- Research Tools & Software
- Writing & Publishing
- Time Management & Productivity
- Mental Health & Wellbeing
- Career Development
- Academic Skills

*Know of a great resource? Consider contributing to help other PhD students!*
