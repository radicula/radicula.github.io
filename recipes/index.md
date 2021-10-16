---
layout: default
title: "recipes"
---

this is maybe 90% of everything I have eaten in the past 3 years. this is mostly for my own easy reference

(in progress, being migrated here)

{% for post in site.categories.recipes %}

- [{{ post.title }}]({{ post.url }}) ({{ post.date | date_to_string }})

{% endfor %}
