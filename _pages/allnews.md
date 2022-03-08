---
title: "News"
layout: textlay
excerpt: "Curtis Lab."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }}</p>
<br>{{ article.headline | markdownify}}
{% endfor %}
