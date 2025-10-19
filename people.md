---
layout: page
title: People
permalink: /people/
---

# People Directory

Connect with PhD students, researchers, and academics from around the world. Browse profiles to find people in your field, potential collaborators, or mentors.

## All Profiles

{% for person in site.people %}
<div class="person-card" style="margin-bottom: 2em; padding: 1em; border-left: 3px solid #828282;">
  <h3><a href="{{ person.url | relative_url }}">{{ person.name }}</a></h3>
  <p><strong>{{ person.position }}</strong> | {{ person.institution }}</p>
  <p>{{ person.excerpt }}</p>
  
  {% if person.email or person.website or person.twitter or person.linkedin or person.github %}
  <p style="margin-top: 0.5em;">
    {% if person.email %}
    <a href="mailto:{{ person.email }}" title="Email">📧</a> 
    {% endif %}
    {% if person.website %}
    <a href="{{ person.website }}" target="_blank" title="Website">🌐</a> 
    {% endif %}
    {% if person.twitter %}
    <a href="https://twitter.com/{{ person.twitter }}" target="_blank" title="Twitter">🐦</a> 
    {% endif %}
    {% if person.linkedin %}
    <a href="{{ person.linkedin }}" target="_blank" title="LinkedIn">💼</a> 
    {% endif %}
    {% if person.github %}
    <a href="https://github.com/{{ person.github }}" target="_blank" title="GitHub">💻</a> 
    {% endif %}
  </p>
  {% endif %}
</div>
{% endfor %}

---

