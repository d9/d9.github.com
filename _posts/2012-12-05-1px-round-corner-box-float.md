---
layout: post
title: "1px圆角 无背景图(float) "
description: "float实现 无需hack"
category:
 - css
tags: [float, 圆角, 无背景图]
---
{% include JB/setup %}

<h4>效果预览</h4>

<div class="preview" id="preview"><p class="rbf">
  <span><span>今天</span></span>
  <span class="on"><span>昨天</span></span>
</p>
</div>

<style type="text/css" id="cssR">.rbf{*zoom:1;overflow:hidden;}
.rbf span{float:left;height:20px;margin-left:6px;}
.rbf span span{float:left;padding:2px 3px 0;margin-top:1px;height:16px;line-height:16px;position:relative;}
.rbf span.on{background:#369;color:#fff;}
.rbf span.on span{background:#369;margin:1px -1px 0;}
</style>