---
layout: page
title: /code
---
{% include JB/setup %}

a collection of a few of my projects and scripts

{% for repository in site.github.public_repositories %}
  {% unless repository.fork or repository.name == site.github.repository_name %}
  {% if repository.description %}
  * [{{ repository.name }}]({{ repository.html_url }}) - {{ repository.description }}
  {% else %}
  * [{{ repository.name }}]({{ repository.html_url }})
  {% endif %}
  {% endunless %}
{% endfor %}
