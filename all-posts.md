---
layout: page
title: "All Posts (Debug)"
permalink: /all-posts/
---

Below is a debug list of posts that Jekyll sees:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>