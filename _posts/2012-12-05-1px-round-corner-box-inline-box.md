---
layout: post
title: "1px圆角 无背景图(inline block)"
description: "inline-block实现 ie6/7需要hack"
category:
 - css
tags: [inline-block, 圆角, 无背景图]
---
{% include JB/setup %}

<h4>效果预览</h4>

<div class="preview" id="preview"><p class="rbi">
  <span class="on"><span>今天</span>
  </span><span><span>昨天</span></span>
</p>
</div>

<style type="text/css" id="cssR">.rbi span{display:inline-block;height:20px;line-height:20px;margin-left:6px;}
.rbi span span{display:inline-block;padding:2px 3px 0;margin-top:1px;height:16px;line-height:16px;position:relative;}
.rbi span.on{background:#369;color:#fff;}
.rbi span.on span{background:#369;margin:1px -1px 0;*left:-1px;}
</style>