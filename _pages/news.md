---
layout: page
permalink: /news/
title: news
description:
nav: false
---

<div class="news">
  {% assign news = site.news | reverse %}
  {% for item in news %}
    <div class="news-item">
      <span class="news-date">{{ item.date | date: "%b %-d, %Y" }}</span>
      {% if item.inline %}
        {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
      {% else %}
        <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
        {{ item.excerpt | remove: '<p>' | remove: '</p>' | emojify }}
      {% endif %}
    </div>
  {% endfor %}
</div>
