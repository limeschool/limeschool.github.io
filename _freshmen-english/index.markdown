---
title: index
date: 2017-10-12 18:29:00 -04:00
layout: page
---

{% for item in site.freshmen_english %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}