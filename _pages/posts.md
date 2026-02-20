---
layout: single
title: Posts
author_profile: false
permalink: /posts/
---

{% for post in site.posts %}
<div class="post-list-item">
<h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
<span class="post-date">{{ post.date | date: "%B %-d, %Y" }}</span>
<p class="post-excerpt">{{ post.excerpt | strip_html }}</p>
</div>

{% endfor %}
