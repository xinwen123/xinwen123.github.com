---
layout: landing
title: 新闻聚合
head_title: 新闻聚合
description: |
  收集各大门户网站的热点，实时新闻。
---

<div class="row" style="margin-bottom:20px;">
  <div style="width:100%">
    <h3 style="margin-bottom:5px; margin-left:20px; color:#333333;">看新闻，尽在新闻聚合网。</h3>
    <h6 align="right" style="font-size:12px; margin-right:8px">喜欢我，可以把它加入你的<a href="javascript:void(0)" onclick="window.external.AddFavorite(location.href, document.title)">收藏夹</a>吧！</h6>
  </div>
  <div class="divbox" style="width:96%;margin-right:0px;padding-right:10px;">
    <h1 id="start-now" style="margin-left: 0px; margin-right: 0px; font-size: 22px;">最新新闻</h1>
    <div style="margin-left:-15px">
    {% assign posts_all = site.posts %}
    {% assign count = 10 %}
    {% include custom/posts_all %}
  </div>
  </div>
  
</div>

