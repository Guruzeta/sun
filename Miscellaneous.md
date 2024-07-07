---
layout: post
title: Miscellaneous
---

# Miscellaneous

<ul>
  {% for post in site.miscellaneous %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>