---
title: "Noticias"
layout: page
sitemap: false
permalink: /allnews/
---

# Noticias

{% for article in site.data.news %}
<p>{{ article.date }} <br>
{{ article.headline }}</p>
{% endfor %}