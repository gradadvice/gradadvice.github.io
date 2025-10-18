---
layout: page
title: Advice
permalink: /advice/
---

# PhD Advice

This section contains practical advice and guidance for PhD students at various stages of their doctoral journey.

## Available Topics

{% for advice in site.advice %}
- [{{ advice.title }}]({{ advice.url | relative_url }})
  {{ advice.excerpt }}
{% endfor %}

---

## Can't Find What You're Looking For?

If you have a specific question or topic you'd like to see covered, please consider contributing or opening an issue on our GitHub repository.
