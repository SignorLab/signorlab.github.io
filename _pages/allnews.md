---
title: "News"
layout: textlay
excerpt: "Signor Lab at NDSU."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
{{ article.date }} <br>
{{ article.headline | markdownify}}
{% endfor %}
