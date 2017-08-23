---
layout: default
---

# Notes

<ul>
    {% assign weeks = site.posts | where: 'categories', 'week' %}
    {% for post in weeks %}
        {% assign pic_root = "/assets/images/" | relative_url %}
        <li class="showcase-list" style="background-image: url({{ pic_root | append: post.image }})">
                <a href="..{{ post.url }}">{{ post.title }}</a>
                <br>
                {{post.date}}
        </li>
    {% endfor %}
</ul>
