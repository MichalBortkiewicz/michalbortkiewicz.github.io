---
layout: default
title: "Blog"
---


## Here you can find some more or less interesting thoughts

  
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
