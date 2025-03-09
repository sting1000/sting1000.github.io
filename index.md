---
layout: home
author_profile: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header-bg.jpg
  actions:
    - label: "了解更多"
      url: "/about/"
excerpt: >
  算法工程师到AI产品经理的转型之旅<br />
  <small>技术背景 + 产品思维 = 卓越的AI产品</small>
feature_row:
  - image_path: /assets/images/project-1.jpg
    alt: "项目1"
    title: "特色项目一"
    excerpt: "结合NLP技术与产品设计的企业级解决方案"
    url: "/projects/project-1/"
    btn_class: "btn--primary"
    btn_label: "了解详情"
  - image_path: /assets/images/project-2.jpg
    alt: "项目2"
    title: "特色项目二"
    excerpt: "算法模型在实际业务场景中的应用与优化"
    url: "/projects/project-2/"
    btn_class: "btn--primary"
    btn_label: "了解详情"
  - image_path: /assets/images/blog-1.jpg
    alt: "博客文章"
    title: "技术与产品的平衡"
    excerpt: "如何利用算法背景做出更好的产品决策"
    url: "/blog/tech-product-balance/"
    btn_class: "btn--primary"
    btn_label: "阅读全文"
---

<div style="margin-bottom: 3em;">
  <h2>欢迎来到我的专业作品集</h2>
  <p>我是一名拥有扎实算法背景的工程师，正在向AI产品经理方向发展。我的使命是将深厚的技术知识与产品思维相结合，打造出卓越的AI解决方案。</p>
  
  <h3>专业技能</h3>
  <ul class="skill-list">
    <li><strong>技术能力:</strong> 机器学习/深度学习、自然语言处理、计算机视觉、大规模分布式系统</li>
    <li><strong>产品能力:</strong> 需求分析、用户研究、产品规划、敏捷开发、数据驱动决策</li>
    <li><strong>通用能力:</strong> 跨团队协作、技术沟通、项目管理、商业敏感度</li>
  </ul>
</div>

{% include feature_row %}

## 最新思考

<div class="latest-thoughts">
  {% for post in site.posts limit:3 %}
    <div class="thought-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="page__meta">
        <i class="far fa-calendar-alt" aria-hidden="true"></i> {{ post.date | date: "%Y年%m月%d日" }}
      </p>
      <p class="archive__item-excerpt">{{ post.excerpt }}</p>
      <p><a href="{{ post.url | relative_url }}" class="btn btn--small btn--primary">继续阅读</a></p>
    </div>
  {% endfor %}
</div> 