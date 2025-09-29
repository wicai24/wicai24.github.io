---
layout: single
title: Posts
author_profile: true
permalink: /posts/
---

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
<small>{{ post.date | date: "%B %-d, %Y" }}</small>

{{ post.excerpt | strip_html }}

{% unless forloop.last %}---{% endunless %}

{% endfor %}
