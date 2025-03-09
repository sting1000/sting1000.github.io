---
layout: default
---

<div class="banner">
  <h1>算法转AI产品作品集</h1>
  <p>技术背景 + 产品思维 = 卓越的AI产品</p>
</div>

<div class="feature-section">
  <h2>欢迎来到我的专业作品集</h2>
  <p>我是一名拥有扎实算法背景的工程师，正在向AI产品经理方向发展。我的使命是将深厚的技术知识与产品思维相结合，打造出卓越的AI解决方案。</p>
  
  <h3>专业技能</h3>
  <div>
    <span class="skill-tag">机器学习</span>
    <span class="skill-tag">深度学习</span>
    <span class="skill-tag">自然语言处理</span>
    <span class="skill-tag">计算机视觉</span>
    <span class="skill-tag">分布式系统</span>
    
    <span class="skill-tag product">需求分析</span>
    <span class="skill-tag product">用户研究</span>
    <span class="skill-tag product">产品规划</span>
    <span class="skill-tag product">敏捷开发</span>
    
    <span class="skill-tag soft">跨团队协作</span>
    <span class="skill-tag soft">技术沟通</span>
    <span class="skill-tag soft">项目管理</span>
  </div>
</div>

## 特色项目

<div class="two-column">
  <div class="card">
    <h3>智能客服NLP引擎</h3>
    <p>结合NLP技术与产品设计的企业级解决方案，提升客服效率80%</p>
    <a href="/projects/project-1/" class="btn">了解详情</a>
  </div>
  
  <div class="card">
    <h3>推荐系统优化与产品化</h3>
    <p>将复杂的推荐算法转化为易用的产品功能，提升用户停留时间35%</p>
    <a href="/projects/project-2/" class="btn">了解详情</a>
  </div>
</div>

## 最新思考

{% for post in site.posts limit:3 %}
<div class="card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.url | relative_url }}" class="btn btn-secondary">继续阅读</a>
</div>
{% endfor %} 