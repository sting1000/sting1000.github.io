# 苏哲宸 | AI解决方案与产品专家个人网站

这是一个基于Jekyll框架和GitHub Pages构建的个人专业网站，展示我作为AI解决方案架构师和5G技术专家的专业背景、项目经验和技术思考。

## 网站概览

- **首页**: 个人简介、核心专长和专业经历亮点
- **关于我**: 详细的工作经历、教育背景和技能专长
- **项目**: 技术项目案例详情，展示解决方案架构能力
- **思考**: 技术博客，分享对AI、5G技术和产品落地的见解
- **联系**: 专业联系方式和简历下载

## 技术栈

- Jekyll静态网站生成器
- 自定义响应式设计，采用蓝色系莫兰迪色彩方案
- Markdown内容管理
- GitHub Pages托管
- 移动端优化的响应式设计

## 本地开发指南

1. 安装必要环境:
   ```bash
   # 安装Ruby (推荐使用Ruby版本管理器如rbenv)
   brew install ruby
   
   # 安装Jekyll和Bundler
   gem install jekyll bundler
   ```

2. 克隆仓库:
   ```bash
   git clone https://github.com/sting1000/sting1000.github.io.git
   cd sting1000.github.io
   ```

3. 安装依赖:
   ```bash
   bundle install
   ```

4. 本地运行服务器:
   ```bash
   bundle exec jekyll serve
   ```

5. 在浏览器中访问 `http://localhost:4000` 预览网站

## 网站维护指南

### 更新个人信息

1. 编辑 `_config.yml` 文件更新基本信息:
   - 网站标题、副标题
   - 个人描述
   - 社交媒体链接

2. 编辑 `index.md` 和 `_pages/about.md` 更新详细个人资料

### 添加/更新项目案例

1. 在 `_projects` 目录中创建或编辑Markdown文件
2. 文件命名推荐: `project-name.md`
3. 文件格式示例:
   ```yaml
   ---
   layout: project
   title: "项目名称"
   excerpt: "简短描述"
   header:
     image: /assets/images/projects/project-header.jpg
   ---
   
   ## 项目背景
   
   描述项目背景和业务需求...
   
   ## 技术挑战
   
   列出主要技术挑战...
   
   ## 解决方案
   
   详细说明您的解决方案...
   
   ## 业务成果
   
   量化项目成果...
   ```

### 发布博客文章

1. 在 `_posts` 目录中创建新的Markdown文件
2. 文件命名格式: `YYYY-MM-DD-article-title.md`
3. 文件格式示例:
   ```yaml
   ---
   layout: post
   title: "文章标题"
   date: YYYY-MM-DD
   categories:
     - 技术
     - 思考
   tags:
     - AI
     - 5G
   ---
   
   文章正文内容...
   ```

### 更新样式

1. 主要样式定义在 `_includes/inline-styles.html`
2. 页面特定样式使用类选择器: `.home`, `.about`, `.projects`, `.blog`, `.contact`
3. 颜色变量定义在CSS `:root` 部分，修改这些变量可以全局更改网站配色

### 添加新页面

1. 在 `_pages` 目录创建新的Markdown文件
2. 设置页面Front Matter:
   ```yaml
   ---
   layout: default
   title: 页面标题
   permalink: /custom-url/
   ---
   ```
3. 在 `_config.yml` 的 `main` 部分添加导航链接

## 部署流程

网站采用GitHub Pages自动部署:

1. 本地修改后，提交并推送到GitHub:
   ```bash
   git add .
   git commit -m "描述您的更新"
   git push origin master
   ```

2. GitHub Actions会自动构建并部署网站
3. 几分钟后，更改将在 https://sting1000.github.io 生效

## 故障排查

- **样式问题**: 检查 `_includes/inline-styles.html` 和浏览器开发者工具
- **页面404**: 确认 `permalink` 设置正确且文件位于正确目录
- **图片不显示**: 确认路径正确，GitHub Pages区分大小写

## 目录结构说明

```
sting1000.github.io/
├── _config.yml          # 网站配置文件
├── _data/               # 导航等数据
├── _includes/           # 可重用组件
├── _layouts/            # 页面布局模板
├── _pages/              # 主要页面内容
├── _posts/              # 博客文章
├── _projects/           # 项目案例
├── assets/              # 静态资源(图片、CSS、JS)
├── index.md             # 首页内容
└── README.md            # 项目说明文档
```

---

© 2025 苏哲宸. 保留所有权利。 