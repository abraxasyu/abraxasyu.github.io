---
layout: default
---

## About

I am a Biomedical Engineering graduate student at the Institute for Informatics at Washington University School of Medicine, studying Biomedical Informatics.

## Blog Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

## Formatting Reference

[Link](./another-page.html).
