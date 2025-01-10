---
layout: default
title: Resources
permalink: /resources/
---

# Healthcare Technology Resources

Welcome to our resource library. Here you'll find informative articles about patient engagement, healthcare technology, and AI-powered medical solutions.

{% for resource in site.resources %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
{% endfor %}
