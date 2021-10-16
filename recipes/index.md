---
layout: default
title: "recipes"
---

{% for recipe in site.recipes.recipes %}

{{ recipe.date | date_to_string }} - [{{ recipe.title }}]({{ recipe.url }}) {% endfor %}
