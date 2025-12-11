---
layout: default
title: Articles
---

{% for post in site.posts %}
<article class="post">
  <div class="post-meta">
    {{ post.date | date: "%b %-d, %Y" }}
  </div>
  <h2 class="post-title">
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </h2>
  <p class="post-excerpt">
    {{ post.excerpt | strip_html | truncate: 220 }}
  </p>
</article>
{% endfor %}