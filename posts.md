---
layout: page
title: Posts
permalink: /posts/
---

# Posts
<p class="subtitle">Updates, field notes, and reflections</p>

{% for post in site.posts %}
- **{{ post.date | date: "%b %d, %Y" }}** — [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}
