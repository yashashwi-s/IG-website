---
title: "Blogs"
layout: default
permalink: /blogs
---

# Blogs

Welcome to the Blogs section! Here you will find all the latest blog posts and articles from the COPS IG team.

Check out COPS blogs at [Hashnode](https://blogs.copsiitbhu.co.in/).

---

{% for post in site.data.posts %}
<div style="margin-bottom: 20px; border-bottom: 1px solid #ccc; padding-bottom: 10px;">
  <h3>
    <a href="{{ post.link.url }}">
      {{ post.title }}
    </a>
  </h3>
  <p>{{ post.description }}</p>
  <p style="text-align: right; font-size: 0.9em; font-style: italic;">
    <a href="{{ post.authorsurl }}">{{ post.authors }}</a>
  </p>
</div>
{% endfor %}



