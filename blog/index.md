---
layout: page
title: /blog
---
{% include JB/setup %}

{% if site.posts != empty %}
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
{% else %}
nothing yet
{% endif %}
