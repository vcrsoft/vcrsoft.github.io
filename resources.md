---
layout: default
title: Resources
permalink: /resources/
---

# AI Lead Qualification for Home Service Pros

Learn how an AI-powered **lead qualification chatbot** can transform your home service business. From pre-qualifying leads to delivering polished, actionable reports, this virtual assistant helps you focus on real opportunities, cut wasted trips, and respond faster—all without lifting a phone.

{% for resource in site.resources %}
  {% unless resource.path contains "_resources/examples/" %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
{% endfor %}
