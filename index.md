---
layout: default
---

Welcome to The Cookbook! Here you'll find a collection of recipes that I enjoy.

## Recipes

<ul>
{% for recipe in site.recipes %}
  <li><a href="{{ site.baseurl }}{{ recipe.url }}">{{ recipe.title }}</a></li>
{% endfor %}
</ul>
