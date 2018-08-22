---
layout: mygood
title: stdio2016 的部落格
---
嗶嗶！系<span id="系統錯誤" style="display:inline-block;  transform:scalex(0.5);"><span>糸</span>充<span>金</span>昔<span>言</span>吳</span>！您所看到的是史上最樸素的部落格，因為我 ~~沒有美感~~（誤）覺得只要寫好文章就夠了

<script>
var s = 系統錯誤.parentNode.style;
var prefixes = ["transform", "msTransform", "MozTransform", "WebkitTransform", "OTransform"];
for (var i = 0; i < prefixes.length; i++) {
  if (s[prefixes[i]] !== undefined) {
    系統錯誤.className += " supports-transform";
    break;
  }
}
</script>

*新功能！* 如果你有 GitHub 帳號，你還可以在我的文章的最後面留言喔

以下是我寫的文章：

{% for post in site.posts %}{% unless post.draft %}
- <span class="post-meta">{{ post.date | date: "%Y 年 %-m 月 %-d 日" }}</span>
  <h2 class="post-title"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
{% endunless %}{% endfor %}
