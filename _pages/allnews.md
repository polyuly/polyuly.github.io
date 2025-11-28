---
title: "News"
layout: default
permalink: /allnews.html
sitemap: false
---

<h2>News</h2>

<div class="news-list">
{% for article in site.data.news %}
<div class="news-card clearfix">

<div class="news-card-body">
<div class="news-card-date">{{ article.date }}</div>
<div class="news-card-text">
{{ article.headline | markdownify }}
</div>
</div>

{% if article.image %}
<div class="news-card-image">
<img src="{{ site.url }}{{ site.baseurl }}{{ article.image }}" alt="News image" class="news-img">
</div>
{% endif %}

</div>
<hr>
{% endfor %}
</div>

