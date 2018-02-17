---
layout: mygood
title: stdio2016 的部落格
---
哈哈，被我騙了，裡面什麼都沒有，對吧……

其實是因為我還沒寫好文章，，哈哈哈！！！！！

不過你可以按[這裡](2018/02/13)找找最新文章

{% for post in site.posts %}
- <span class="post-meta">{{ post.date | date: "%Y 年 %-m 月 %-d 日" }}</span>
  <h2 class="post-title"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
{% endfor %}
