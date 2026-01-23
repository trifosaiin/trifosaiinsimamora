---
layout: page
title: Posts
permalink: /posts/
---

<p class="subtitle">Field updates, reflections, and research notes</p>

{% for post in site.posts %}
<div style="margin-bottom: 25px;">
  <div style="font-size:14px; color:#666;">
    {{ post.date | date: "%B %d, %Y" }}
  </div>
  <div style="font-size:20px; font-weight:600;">
    <a href="{{ post.url | relative_url }}">
      {{ post.title }}
    </a>
  </div>
</div>
{% endfor %}
