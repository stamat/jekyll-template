---
layout: default
title: Jekyll Boilerplate
description: Just a simple boilerplate for Jekyll to get you started with your next project.
---

# {{ page.title }}

{{ page.description }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
