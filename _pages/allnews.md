---
title: News
layout: textlay
excerpt: Human Augmentation Lab (HAL).
sitemap: false
permalink: /allnews.html
published: true
---

# News

{% for article in site.data.news %}
<p><b>{{ article.date }}</b> <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
