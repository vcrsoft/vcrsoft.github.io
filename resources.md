---
layout: default
title: Resources
permalink: /resources/
---

# Healthcare Technology Resources

Welcome to our resource library. Here you'll find informative articles about patient engagement, healthcare technology, and AI-powered medical solutions.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt | markdownify }}

[Read more]({{ post.url | relative_url }})

---
{% endfor %}
