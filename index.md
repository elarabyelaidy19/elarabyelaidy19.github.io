---
layout: default
---

# Welcome to My Minimal GitHub Website

This is the home page of my minimal GitHub website. Here you'll find my latest posts and updates.

## Recent Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <br>
      <small>{{ post.date | date: "%B %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>