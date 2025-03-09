# 算法工程师转型AI产品经理作品集网站

这是一个基于Jekyll框架和GitHub Pages构建的个人作品集网站，旨在展示我从算法工程师向AI产品经理的转型历程和专业能力。

## 网站结构

- **首页**: 个人简介、核心技能和精选项目展示
- **关于我**: 详细的专业背景、技能列表和转型故事
- **项目**: 详细的项目案例，展示技术与产品思维的结合
- **思考**: 博客文章，分享关于AI产品、技术与产品平衡等主题的思考
- **联系**: 联系方式和简历下载

## 技术栈

- Jekyll静态网站生成器
- Minimal Mistakes主题
- Markdown内容管理
- GitHub Pages托管
- 响应式设计，移动端友好

## 本地开发

1. 安装Ruby和Jekyll:
   ```bash
   # macOS
   brew install ruby
   gem install jekyll bundler
   
   # Ubuntu
   sudo apt-get install ruby-full build-essential
   gem install jekyll bundler
   ```

2. 克隆仓库:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```

3. 安装依赖:
   ```bash
   bundle install
   ```

4. 本地运行:
   ```bash
   bundle exec jekyll serve
   ```

5. 在浏览器中访问 `http://localhost:4000`

## 内容更新

### 添加新项目

1. 在`_projects`文件夹中创建新的Markdown文件
2. 设置Front Matter:
   ```yaml
   ---
   title: "项目名称"
   excerpt: "项目简介"
   header:
     image: /assets/images/project-header.jpg
     teaser: /assets/images/project-teaser.jpg
   sidebar:
     - title: "角色"
       text: "你在项目中的角色"
     - title: "技术栈"
       text: "使用的技术"
   ---
   ```
3. 编写项目内容，建议包含:
   - 项目背景
   - 挑战
   - 解决方案
   - 技术与产品结合点
   - 业务成果
   - 经验总结

### 添加新博客文章

1. 在`_posts`文件夹中创建新的Markdown文件，命名格式为`YYYY-MM-DD-title.md`
2. 设置Front Matter:
   ```yaml
   ---
   title: "文章标题"
   categories:
     - 分类
   tags:
     - 标签1
     - 标签2
   toc: true
   ---
   ```
3. 编写文章内容

## 部署

网站会在推送到GitHub仓库的main分支后自动部署。确保你的仓库遵循`username.github.io`的命名格式。

## 定制化

- `_config.yml`: 主要配置文件
- `assets/css/custom.css`: 自定义样式
- `_data/`: 导航菜单等数据文件

## 联系方式

如有任何问题或建议，请通过以下方式联系我:
- Email: your.email@example.com
- GitHub: [yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourusername)

---

© 2023 您的名字. 保留所有权利。 