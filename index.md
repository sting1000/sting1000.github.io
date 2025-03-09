---
layout: default
---

<div class="banner">
  <h1>苏哲宸</h1>
  <p>AI解决方案架构师 · 5G技术专家 · EPFL计算机科学硕士</p>
</div>

<div class="profile-section">
  <div class="profile-photo">
    <img src="/assets/images/profile-photo.jpg" alt="苏哲宸照片">
  </div>
  <div class="profile-intro">
    <h2>您好，欢迎访问我的专业空间</h2>
    <p>作为一名AI解决方案架构师和5G技术专家，我致力于将前沿技术转化为实际商业价值。</p>
    <div class="profile-links">
      <a href="/about/" class="btn">了解更多</a>
      <a href="/contact/" class="btn btn-outline">联系我</a>
    </div>
  </div>
</div>

<div class="feature-section">
  <h2>专业简介</h2>
  <p>我是一名拥有深厚技术背景的AI解决方案架构师，专注于AR/VR环境下的计算机视觉、5G通信技术以及边缘计算解决方案。凭借在华为三年多的丰富经验，我擅长将尖端算法与真实业务需求相结合，打造兼具技术创新性与商业价值的产品方案。</p>
  
  <h3>核心专长</h3>
  <div>
    <span class="skill-tag">AI算法设计</span>
    <span class="skill-tag">深度学习</span>
    <span class="skill-tag">计算机视觉</span>
    <span class="skill-tag">5G网络优化</span>
    <span class="skill-tag">AR/VR解决方案</span>
    
    <span class="skill-tag product">解决方案架构</span>
    <span class="skill-tag product">性能优化</span>
    <span class="skill-tag product">商业化落地</span>
    <span class="skill-tag product">技术路线规划</span>
    
    <span class="skill-tag soft">跨团队协作</span>
    <span class="skill-tag soft">技术沟通</span>
    <span class="skill-tag soft">国际化视野</span>
  </div>
</div>

## 专业经历亮点

<div class="two-column">
  <div class="card">
    <h3>AR环境深度估计算法</h3>
    <p>设计了亚厘米级精度的深度估计算法，显著提升AR应用中的空间感知能力与交互体验。</p>
    <a href="/projects/ar-depth-estimation/" class="btn">了解详情</a>
  </div>
  
  <div class="card">
    <h3>5G资源分配策略创新</h3>
    <p>开创性地设计了RedCap SRS资源分配策略，已被菲律宾Dito采用，服务超过100万用户。</p>
    <a href="/projects/redcap-strategy/" class="btn">了解详情</a>
  </div>
</div>

<div class="two-column">
  <div class="card">
    <h3>场景识别实时优化</h3>
    <p>优化场景识别算法，实现FPS提升30%的实时处理能力，同时保持识别准确率。</p>
    <a href="/projects/scene-recognition/" class="btn">了解详情</a>
  </div>
  
  <div class="card">
    <h3>FWA业务加速模型</h3>
    <p>为沙特Zain运营商打造FWA业务加速模型，提升游戏/视频体验质量40%。</p>
    <a href="/projects/fwa-acceleration/" class="btn">了解详情</a>
  </div>
</div>

## 教育背景

<div class="feature-section education-section">
  <div class="education-item">
    <h3>瑞士洛桑联邦理工学院 (EPFL)</h3>
    <p>计算机科学硕士学位<br>2018年9月 - 2021年10月</p>
  </div>
  
  <div class="education-item">
    <h3>电子科技大学</h3>
    <p>计算机科学与技术学士学位<br>2014年 - 2018年</p>
  </div>
</div>

## 最新见解

{% for post in site.posts limit:2 %}
<div class="card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt }}</p>
  <a href="{{ post.url | relative_url }}" class="btn btn-secondary">继续阅读</a>
</div>
{% endfor %} 