---
layout: default
title: Resources
permalink: /resources/
---

# AI Diagnostic Automation for Commercial Service Pros

Explore how an AI-powered **diagnostic chatbot** can streamline service intake for your commercial clients — restaurants, apartments, hotels, or offices.  
Instead of phone calls or vague service requests, your chatbot gathers detailed fault information automatically and delivers a structured diagnostic report to your inbox.

This approach helps your team prepare better, eliminate wasted diagnostic time, and ensure technicians arrive on-site ready to work.

{% for resource in site.resources %}
  {% unless resource.url contains "/resources/examples/" %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
  {% endunless %}
{% endfor %}
