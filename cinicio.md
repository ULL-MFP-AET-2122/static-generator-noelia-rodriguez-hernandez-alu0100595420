---
layout: single
title: Mis publicaciones inicio
permalink: /inicio
toc: true
---

{%- for post in site.categories["inicio"] %}
* [{{post.title}}]({{post.url}})
{% endfor %}