---
layout: default
title: 思考
permalink: /blog/
---

<div class="banner">
  <h1>思考与分享</h1>
  <p>关于技术、产品和职业发展的见解</p>
</div>

<!-- <div class="feature-section">
  <h2>我的博客</h2>
  <p>在这里，我分享对AI技术、产品设计和职业发展的思考。这些文章记录了我从算法工程师到产品经理的转型过程中的收获与洞察。</p>
</div> -->

{% for post in site.posts %}
<div class="card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p class="post-date">{{ post.date | date: "%Y年%m月%d日" }}</p>
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.url | relative_url }}" class="btn">阅读全文</a>
</div>
{% endfor %}

<div class="feature-section">
  <h2>即将推出的主题</h2>
  <ul>
    <li>大语言模型时代的产品设计挑战</li>
    <li>如何将复杂AI技术转化为易用产品功能</li>
    <li>从工程师到产品经理：技术思维的转变</li>
    <li>AI产品中的数据与隐私平衡</li>
    <li>产品经理应该了解的机器学习基础</li>
  </ul>
</div> 