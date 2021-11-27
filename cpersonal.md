---
layout: single
title: Mi espacio personal
permalink: /personal
toc: true
---

{%- for post in site.categories["personal"] %}
* [{{post.title}}]({{post.url}})
{% endfor %}