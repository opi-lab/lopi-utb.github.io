---
title: "Noticias"
layout: page
sitemap: false
permalink: /allnews/
---

# Noticias

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline }}
{% endfor %}