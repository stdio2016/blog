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

壓縮字串！！
金融科技&rArr;<span style="display:inline-block;transform:scalex(0.5);margin-left:-0.25em;margin-right:-0.25em;">金</span><span style="display:inline-block;transform:scalex(0.5);margin-left:-0.25em;margin-right:-0.25em;color:brown;">鬲</span><span style="display:inline-block;transform:scalex(0.5);margin-left:-0.25em;margin-right:-0.25em;color:brown;">虫</span><span style="display:inline-block;transform:scalex(0.5);margin-left:-0.25em;margin-right:-0.25em;">科</span>技&rArr;鎘蝌技

以下是我寫的文章：

{% for post in site.posts %}{% unless post.draft %}
- <span class="post-meta">{{ post.date | date: "%Y 年 %-m 月 %-d 日" }}</span>
  <h2 class="post-title"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h2>
{% endunless %}{% endfor %}
