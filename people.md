---
layout: page
title: People
permalink: /people/
---

# People Directory

{% for person in site.people %}
<div class="person-card-minimal">
  <div class="person-info">
    <h3><a href="{{ person.url | relative_url }}">{{ person.name }}</a></h3>
    <p class="person-meta">{{ person.position }} · {{ person.institution }}</p>
  </div>
  
  {% if person.email or person.website or person.twitter or person.linkedin or person.github %}
  <div class="social-links-minimal">
    {% if person.email %}
    <a href="mailto:{{ person.email }}" title="Email" class="social-icon email"><i class="fas fa-envelope"></i></a>
    {% endif %}
    {% if person.website %}
    <a href="{{ person.website }}" target="_blank" rel="noopener noreferrer" title="Website" class="social-icon website"><i class="fas fa-globe"></i></a>
    {% endif %}
    {% if person.twitter %}
    <a href="https://twitter.com/{{ person.twitter }}" target="_blank" rel="noopener noreferrer" title="Twitter" class="social-icon twitter"><i class="fab fa-twitter"></i></a>
    {% endif %}
    {% if person.linkedin %}
    <a href="{{ person.linkedin }}" target="_blank" rel="noopener noreferrer" title="LinkedIn" class="social-icon linkedin"><i class="fab fa-linkedin"></i></a>
    {% endif %}
    {% if person.github %}
    <a href="https://github.com/{{ person.github }}" target="_blank" rel="noopener noreferrer" title="GitHub" class="social-icon github"><i class="fab fa-github"></i></a>
    {% endif %}
  </div>
  {% endif %}
</div>
{% endfor %}

