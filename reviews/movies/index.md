---
layout: default
title: "movies (and maybe tv idk)"
---

i have very good taste !

(will be migrated here soon)

{% for post in site.categories.movies %}

- {{ post.date | date_to_string }} - [{{ post.title }}]({{ post.url }})

{% endfor %}
