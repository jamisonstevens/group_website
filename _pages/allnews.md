---
title: "Home"
layout: textlay
excerpt: "The Hydroinformatics Group at the University of Virginia."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
