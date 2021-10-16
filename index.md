---
layout: default
title: welcome
---

hello! 

- [some recipes](/recipes)
- [movie reviews (coming soon)]
- [book reviews (coming soon)]

web log:
{% for post in site.categories.weblog %}
* {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
