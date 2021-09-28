---
layout: default
title: Blog
permalink: /blog/
---

# 📝 My Blog Posts

<ul class="posts">

<div class="cp-listing">

{% for post in site.posts %}
  <h4 class="p-title"><a href="{{ post.url | relative_url }}" title="{{ post.title }}">{{ post.title }}</a></h4>
  <p class="p-desc">{{ post.description }}</p>
  <p class="p-date">{{ post.date | date_to_string}} &nbsp;·&nbsp;
  {% for tag in post.tags %}
    {{ tag }}
  {% endfor %}
{% endfor %}
</p>