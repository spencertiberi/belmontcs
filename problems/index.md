---
layout: default
---

# Problems

<ul>
    {% assign problems = site.posts | where: 'categories', 'problems' %}
    {% for post in problems %}
        {% assign pic_root = "/assets/images/" | relative_url %}
        <li>
            <div class="showcase-list">
                <img src="{{ pic_root | append: post.image }}">
                <a href="..{{ post.url }}">{{ post.title }}</a>
                <br>
                <div class="date">{{post.date | date: "%A, %B %d, %Y" }}</div>
            </div>
        </li>
    {% endfor %}
</ul>
