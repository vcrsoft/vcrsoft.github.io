---
layout: default
title: Resources
permalink: /resources/
---

# Remote Diagnostics & Instant Estimates for Pros

Understand how AI-powered **remote diagnostic chatbots** can fundamentally transform your home service business, from pre-qualifying leads to delivering instant, accurate free estimates—all without picking up the phone.

{% for resource in site.resources %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
{% endfor %}
