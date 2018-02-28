---
layout: mygood
title: stdio2016 的部落格
---
嗶嗶！系糸充金昔言吳！您所看到的是史上最樸素的部落格，因為我 ~~沒有美感~~（誤）覺得只要寫好文章就夠了

以下是我寫的文章：

{% for post in site.posts %}
- <span class="post-meta">{{ post.date | date: "%Y 年 %-m 月 %-d 日" }}</span>
  <h2 class="post-title"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
{% endfor %}
