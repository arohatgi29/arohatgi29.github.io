---
layout: page
permalink: /news/
title: news
nav: true
nav_order: 2
---

{% assign news = site.news | sort: "date" | reverse %}
{% for item in news %}
<div class="news-item">
  <span class="news-date">{{ item.date | date: "%B %d, %Y" }}</span>
  <p>{{ item.content }}</p>
</div>
{% endfor %}