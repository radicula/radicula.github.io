---
layout: default
title: "recipes"
---

{% for post in site.categories.recipes %}

- {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})

{% endfor %}
