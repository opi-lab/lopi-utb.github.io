---
title: "Noticias"
layout: page
subtitle: "OPILab at Universidad Tecnologica de Bolivar."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}