---
title: "联系"
permalink: /contact/
author_profile: true
---

## 联系方式

如果您对我的专业背景或项目感兴趣，或者有合作机会，欢迎通过以下方式联系我：

<div class="contact-info">
  <div class="contact-item">
    <i class="fas fa-envelope"></i> <strong>邮箱:</strong> 
    <a href="mailto:your.email@example.com">your.email@example.com</a>
  </div>
  
  <div class="contact-item">
    <i class="fab fa-linkedin"></i> <strong>LinkedIn:</strong> 
    <a href="https://linkedin.com/in/yourusername" target="_blank">linkedin.com/in/yourusername</a>
  </div>
  
  <div class="contact-item">
    <i class="fab fa-github"></i> <strong>GitHub:</strong> 
    <a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a>
  </div>
</div>

## 下载简历

您可以<a href="/assets/files/resume.pdf" target="_blank">下载我的完整简历</a>，了解更多关于我的专业背景和技能。

<div class="form-container">
  <h2>留言</h2>
  <p>您也可以通过以下表单给我留言，我会尽快回复。</p>
  
  <form action="https://formspree.io/f/yourformid" method="POST">
    <div class="form-group">
      <label for="name">姓名</label>
      <input type="text" name="name" id="name" required>
    </div>
    
    <div class="form-group">
      <label for="email">邮箱</label>
      <input type="email" name="email" id="email" required>
    </div>
    
    <div class="form-group">
      <label for="subject">主题</label>
      <input type="text" name="subject" id="subject">
    </div>
    
    <div class="form-group">
      <label for="message">留言内容</label>
      <textarea name="message" id="message" rows="6" required></textarea>
    </div>
    
    <button type="submit" class="btn btn--primary">发送</button>
  </form>
</div>

<style>
  .contact-info {
    margin-bottom: 2em;
  }
  
  .contact-item {
    margin-bottom: 1em;
    font-size: 1.1em;
  }
  
  .form-container {
    margin-top: 3em;
    background-color: #f8f9fa;
    padding: 2em;
    border-radius: 5px;
  }
  
  .form-group {
    margin-bottom: 1.5em;
  }
  
  label {
    display: block;
    margin-bottom: 0.5em;
    font-weight: 600;
  }
  
  input, textarea {
    width: 100%;
    padding: 0.5em;
    border: 1px solid #ddd;
    border-radius: 3px;
  }
  
  textarea {
    resize: vertical;
  }
</style> 