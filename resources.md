---
layout: default
title: Resources
permalink: /resources/
---

# AI Lead Qualification for Home Service Pros

Learn how AI-powered **lead qualification chatbots** can transform your home service business. From pre-qualifying leads to delivering polished, actionable reports, these virtual assistants help you focus on real opportunities, cut wasted trips, and respond faster—all without lifting a phone.

{% for resource in site.resources %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
{% endfor %}
