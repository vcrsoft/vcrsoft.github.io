---
layout: default
title: Resources
permalink: /resources/
---

# Customer Service Chatbots

AI technology, in particular chatbots / assistants / agents, provides a means to enhance the experience and workflow pertaining to all aspects of the customer service process. 

{% for resource in site.resources %}
## [{{ resource.title }}]({{ resource.url | relative_url }})

{{ resource.excerpt | markdownify }}

[Read more]({{ resource.url | relative_url }})

---
{% endfor %}
