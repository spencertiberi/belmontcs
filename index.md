---
layout: default
title: compsci.one
---

# compsci.one

## Stay fly!

[syllabus](syllabus)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
