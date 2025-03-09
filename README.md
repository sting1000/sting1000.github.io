# 苏哲宸 | AI解决方案与产品专家个人网站

这是苏哲宸的个人专业网站，基于Jekyll框架和GitHub Pages构建，展示AI解决方案架构师与5G技术专家的专业背景、项目经验和技术见解。

## 网站概述

这个网站采用了蓝色系莫兰迪色调，设计简洁现代，每个页面都有微妙不同但相互关联的颜色方案，突出专业性和技术特色。主要包含以下内容：

- **首页**: 个人简介、核心专长和专业经历亮点
- **关于我**: 详细的工作经历、教育背景和技术专长
- **项目**: 技术项目案例，展示AI算法和5G技术解决方案
- **思考**: 博客文章，分享关于技术、产品和行业的思考
- **联系**: 联系方式和简历下载

## 技术架构

- **框架**: Jekyll静态网站生成器
- **部署**: GitHub Pages托管
- **样式**: 自定义CSS，莫兰迪色系，响应式设计
- **内容管理**: Markdown
- **版本控制**: Git

## 本地开发指南

1. **环境准备**:
   ```bash
   # 安装Ruby和Jekyll (macOS)
   brew install ruby
   gem install jekyll bundler
   
   # 安装Ruby和Jekyll (Ubuntu/Debian)
   sudo apt-get install ruby-full build-essential
   gem install jekyll bundler
   ```

2. **克隆仓库**:
   ```bash
   git clone https://github.com/sting1000/sting1000.github.io.git
   cd sting1000.github.io
   ```

3. **安装依赖**:
   ```bash
   bundle install
   ```

4. **本地运行**:
   ```bash
   bundle exec jekyll serve
   ```

5. **预览网站**: 浏览器访问 `http://localhost:4000`

## 网站维护指南

### 1. 更新基本信息

网站的基本信息配置在 `_config.yml` 文件中，包括：
- 网站标题、描述和联系信息
- 社交媒体链接
- 导航菜单结构

修改此文件后需要重新启动Jekyll服务器才能生效。

### 2. 页面内容更新

各主要页面的内容位于以下位置：
- 首页: `index.md`
- 关于我: `_pages/about.md`
- 项目页: `_pages/projects.md`和`_projects/`目录下的项目文件
- 博客: `_pages/blog.md`和`_posts/`目录下的文章文件
- 联系页: `_pages/contact.md`

所有页面都使用Markdown格式，顶部包含YAML格式的Front Matter配置区。

### 3. 添加新项目

1. 在`_projects/`目录创建新的Markdown文件，如`project-name.md`
2. 添加Front Matter配置：
   ```yaml
   ---
   layout: project
   title: "项目名称"
   excerpt: "项目简短描述"
   date: 2023-01-01
   header:
     teaser: /assets/images/projects/project-thumbnail.jpg
   ---
   ```
3. 编写项目内容，建议包含：
   - 项目背景与目标
   - 技术难点与挑战
   - 解决方案设计
   - 实施成果与价值
   - 关键技术亮点

### 4. 发布新博客文章

1. 在`_posts/`目录创建新文件，命名格式为`YYYY-MM-DD-title.md`
2. 添加Front Matter配置：
   ```yaml
   ---
   layout: post
   title: "文章标题"
   excerpt: "文章摘要"
   categories: [分类名称]
   tags: [标签1, 标签2]
   ---
   ```
3. 使用Markdown编写文章内容

### 5. 修改网站样式

网站的样式文件位于：
- 内联样式: `_includes/inline-styles.html`（主要颜色方案）
- CSS文件: `assets/css/main.css`（全局样式）

每个页面有独特的颜色方案，通过在`<body>`标签上的类名（home, about, projects, blog, contact）来区分。

### 6. 图片管理

- 所有图片存放在 `assets/images/` 目录
- 建议按照类型创建子目录，如 `projects/`, `posts/`, `general/`
- 上传图片前优化大小，推荐使用WebP格式以获得更好的性能

### 7. 部署更新

将修改推送到GitHub仓库的main分支后，GitHub Pages会自动构建并发布网站：
```bash
git add .
git commit -m "描述你的更新内容"
git push origin main
```

更新通常在几分钟内生效，可以访问 https://sting1000.github.io 查看结果。

## 故障排除

1. **样式未加载**: 检查开发者工具中的网络请求和控制台错误
2. **页面404错误**: 检查文件路径和Front Matter中的permalink设置
3. **构建失败**: 查看GitHub Actions中的构建日志
4. **本地预览与线上不一致**: 确保依赖版本匹配，试着运行`bundle update`

## 联系方式

- GitHub: [sting1000](https://github.com/sting1000)
- LinkedIn: [苏哲宸](https://linkedin.com/in/zhechensu)

---

© 2025 苏哲宸. 保留所有权利。 