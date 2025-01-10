---
layout: default
title: Blog
permalink: /blog/
---

# Blog Posts

{% assign sorted_posts = site.posts | sort: 'date' | reverse %}
{% for post in sorted_posts %}
## [{{ post.title }}]({{ post.url | relative_url }})
{{ post.date | date: "%B %-d, %Y" }}

{{ post.excerpt | markdownify }}

[Read more]({{ post.url | relative_url }})

---
{% endfor %}
