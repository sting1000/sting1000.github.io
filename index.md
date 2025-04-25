---
layout: default
---

<div class="profile-section">
  <div class="profile-image">
    <img src="/assets/images/profile/avatar.jpg" alt="苏哲宸的头像">
  </div>
  <div class="profile-content">
    <h1>你好，我是苏哲宸！</h1>
    <p>我是一名<strong>AI解决方案架构师</strong>，专注于AR/VR环境下的计算机视觉、5G通信技术以及边缘计算解决方案。</p>
    <p>凭借在华为三年多的丰富经验，我擅长将<strong>尖端算法与真实业务需求相结合</strong>，打造兼具技术创新性与商业价值的产品方案。</p>
  </div>
</div>

## 专业经历亮点

<div class="two-column">
  <a href="/projects/" class="project-card">
    <div class="card">
      <div class="card-image">
        <img src="/assets/images/projects/ar-depth.jpg" alt="AR深度估计算法">
      </div>
      <h3>AR环境深度估计算法</h3>
      <p>设计了亚厘米级精度的深度估计算法，显著提升AR应用中的空间感知能力与交互体验。</p>
    </div>
  </a>
  
  <a href="/projects/" class="project-card">
    <div class="card">
      <div class="card-image">
        <img src="/assets/images/projects/5g-resource.jpg" alt="5G资源分配策略">
      </div>
      <h3>5G资源分配策略创新</h3>
      <p>开创性地设计了RedCap SRS资源分配策略，已被菲律宾Dito采用，服务超过100万用户。</p>
    </div>
  </a>
</div>

<div class="two-column">
  <a href="/projects/" class="project-card">
    <div class="card">
      <div class="card-image">
        <img src="/assets/images/projects/scene-recognition.jpg" alt="场景识别优化">
      </div>
      <h3>场景识别实时优化</h3>
      <p>优化场景识别算法，实现FPS提升30%的实时处理能力，同时保持识别准确率。</p>
    </div>
  </a>
  
  <a href="/projects/" class="project-card">
    <div class="card">
      <div class="card-image">
        <img src="/assets/images/projects/fwa-model.jpg" alt="FWA业务加速模型">
      </div>
      <h3>FWA业务加速模型</h3>
      <p>为沙特Zain运营商打造FWA业务加速模型，提升游戏/视频体验质量40%。</p>
    </div>
  </a>
</div>

<div class="section-spacer"></div>

## 教育背景

<div class="feature-section education-section">
  <div class="education-item">
    <div class="education-logo">
      <img src="/assets/images/education/epfl-logo.jpg" alt="EPFL校徽">
    </div>
    <div class="education-content">
      <h3>瑞士洛桑联邦理工学院 (EPFL)</h3>
      <p>计算机科学硕士学位<br>2018年9月 - 2021年10月</p>
    </div>
  </div>
  
  <div class="education-item">
    <div class="education-logo">
      <img src="/assets/images/education/uestc-logo.jpg" alt="电子科技大学校徽">
    </div>
    <div class="education-content">
      <h3>电子科技大学</h3>
      <p>计算机科学与技术学士学位<br>2014年 - 2018年</p>
    </div>
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