---
layout: default
title: Resources
permalink: /resources/
---

# AI-Powered Patient Engagement

AI technology, in particular chatbots / assistants / agents, provides a means to enhance the experience and workflow pertaining to all aspects of the patient engagement process. Benefits include better health outcomes for patients and a more efficient process for the provider.

{% for resource in site.resources %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
{% endfor %}
