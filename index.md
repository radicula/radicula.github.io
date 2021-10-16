---
layout: default
title: welcome
---

hello! 

- [some recipes](/recipes)
- [general thoughts on some media i've consumed](/reviews)

web log:
{% for post in site.categories.weblog %}
* {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
