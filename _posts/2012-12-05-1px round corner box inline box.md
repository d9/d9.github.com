---
layout: post
title: "1pxԲ�� �ޱ���ͼ(inline block)"
description: "inline-blockʵ�� ie6/7��Ҫhack"
category:
 - css
tags: [inline-block,Բ��,�ޱ���ͼ]
---
{% include JB/setup %}

<h4>Ч��Ԥ��</h4>

<div class="preview" id="preview"><p class="rbi">
  <span class="on"><span>����</span>
  </span><span><span>����</span></span>
</p>
</div>

<style type="text/css" id="cssR">.rbi span{display:inline-block;height:20px;margin-left:6px;}
.rbi span span{display:inline-block;padding:2px 3px 0;margin-top:1px;height:16px;line-height:16px;position:relative;}
.rbi span.on{background:#369;color:#fff;}
.rbi span.on span{background:#369;margin:1px -1px 0;*left:-1px;}
</style>