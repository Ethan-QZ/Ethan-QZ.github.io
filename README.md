# GitHub Pages 博客 - 我的AI转型之旅

这是一个基于 Jekyll 的 GitHub Pages 博客，记录了我的 AI 转型历程。

## 目录结构

```
my-ai-blog/
├── _config.yml          # Jekyll 配置
├── _posts/              # 博客文章
│   └── 2026-01-28-my-ai-transformation-journey.md
├── assets/              # 静态资源
│   ├── css/
│   │   └── style.css
│   └── img/             # 图片文件
├── index.md             # 主页
└── README.md            # 说明文件
```

## 如何部署到 GitHub Pages

### 1. 创建 GitHub 仓库
1. 登录 GitHub
2. 创建新仓库，命名为 `yourusername.github.io`（将 `yourusername` 替换为你的 GitHub 用户名）
3. 不要初始化仓库（不添加 README、.gitignore 或 license）

### 2. 配置本地仓库
```bash
cd /home/ubuntu/my-ai-blog
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git branch -M main
git push -u origin main
```

### 3. 启用 GitHub Pages
1. 在 GitHub 仓库页面，转到 Settings
2. 向下滚动到 "Pages" 部分
3. Source 选择 "Deploy from a branch"
4. Branch 选择 "main" 并保持根目录
5. 点击 "Save"

几分钟后，你的博客将在 `https://yourusername.github.io` 可访问。

## 如何添加新文章

在 `_posts` 目录中创建新文件，命名格式为 `YYYY-MM-DD-title.md`：

```markdown
---
layout: post
title: "文章标题"
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [类别1, 类别2]
tags: [标签1, 标签2]
---

# 文章内容

使用 Markdown 语法编写内容...

![图片说明](/assets/img/image.jpg)
```

## 本地预览（可选）

如果想在本地预览，需要安装 Ruby 和 Jekyll：

```bash
gem install bundler jekyll
cd /home/ubuntu/my-ai-blog
bundle install
bundle exec jekyll serve
```

然后在浏览器中访问 `http://localhost:4000`

## 特性

- 响应式设计
- 支持 Markdown 格式
- 图片支持
- 代码高亮
- SEO 友好
- 移动端优化

## 更新日志

- 2026年2月1日: 添加了OpenClaw AI助手集成，自动化博客管理和内容生成
- 2026年1月29日: 发布了关于云原生自动化实践的文章
- 2026年1月28日: 博客上线，发布了第一篇文章"我的AI转型之旅"

