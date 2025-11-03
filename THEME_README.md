# 🚀 科技风 Jekyll 博客主题

一个现代化、极简、具有科技感的 Jekyll 博客主题，采用深色配色方案和流畅的动画效果。

## ✨ 特性

- 🎨 **现代科技风设计** - 深色主题，霓虹色调，几何线条
- 📱 **完全响应式** - 完美适配 PC、平板和手机
- ⚡ **性能优化** - 使用 Tailwind CSS CDN，快速加载
- 🔍 **搜索功能** - 内置搜索界面（可扩展）
- 📐 **数学公式支持** - 集成 MathJax，支持 LaTeX 公式
- 🎭 **优雅动画** - 悬停效果、渐变动画、浮动效果
- ♿ **无障碍优化** - 支持键盘导航和屏幕阅读器
- 🖨️ **打印友好** - 针对打印优化的样式

## 🎯 设计风格

- **配色方案**: 深灰蓝色调 + 青色/紫色高光
- **字体**: Inter (正文) + Space Grotesk (标题)
- **参考**: Apple、Vercel、OpenAI 官网设计风格
- **特色**: 渐变光效、几何线条、背景粒子、霓虹边框

## 📦 文件结构

```
blog/
├── _includes/           # 组件模板
│   ├── head.html       # HTML头部（引入字体和样式）
│   ├── header.html     # 导航栏（含搜索功能）
│   ├── footer.html     # 页脚
│   └── mathjax.html    # 数学公式配置
├── _layouts/           # 页面布局
│   ├── default.html    # 默认布局（含背景效果）
│   ├── home.html       # 首页布局（博客列表）
│   ├── post.html       # 文章页布局
│   └── page.html       # 普通页面布局
├── assets/css/         # 样式文件
│   └── custom.css      # 自定义样式
├── _posts/             # 博客文章
└── _config.yml         # Jekyll 配置
```

## 🚀 快速开始

### 1. 安装依赖

```bash
bundle install
```

### 2. 本地运行

```bash
bundle exec jekyll serve
```

访问 `http://localhost:4000` 查看效果。

### 3. 发布到 GitHub Pages

```bash
git add .
git commit -m "Update blog"
git push origin main
```

## ✍️ 写作指南

### 创建新文章

在 `_posts/` 目录下创建文件，文件名格式：`YYYY-MM-DD-title.md`

```markdown
---
layout: post
title: "文章标题"
date: 2025-11-03 12:00:00 +0800
categories: 技术
tags: [Jekyll, 博客, 教程]
---

这里是文章内容...
```

### 使用数学公式

**行内公式**：
```
这是一个公式 $E = mc^2$ 在文本中。
```

**独立公式块**：
```
$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$
```

### 代码高亮

````markdown
```python
def hello_world():
    print("Hello, World!")
```
````

## 🎨 自定义配置

### 修改网站信息

编辑 `_config.yml`：

```yaml
title: 你的博客名称
email: your-email@example.com
description: 博客描述
url: "https://yourusername.github.io"
github_username: yourusername
```

### 自定义颜色

在 `_includes/head.html` 中的 Tailwind 配置里修改：

```javascript
colors: {
  'tech-dark': '#0a0e17',      // 主背景色
  'tech-cyan': '#06b6d4',       // 主题青色
  'tech-purple': '#8b5cf6',     // 主题紫色
  'tech-glow': '#60a5fa',       // 光晕颜色
}
```

## 📱 响应式断点

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 功能说明

### 搜索功能

点击导航栏的搜索按钮或使用快捷键 `ESC` 关闭。目前为基础界面，可集成：
- Algolia Search
- Lunr.js
- Simple Jekyll Search

### 返回顶部按钮

滚动超过 300px 时自动显示，点击平滑滚动到顶部。

### 文章分享

支持分享到：
- Twitter
- 复制链接功能

## 🌐 浏览器支持

- ✅ Chrome (推荐)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE 11+ (部分效果不支持)

## 📝 待办事项

- [ ] 集成真实搜索功能（Algolia/Lunr.js）
- [ ] 添加评论系统（Disqus/Giscus）
- [ ] 深色/浅色主题切换
- [ ] 文章阅读进度条
- [ ] 目录导航（TOC）
- [ ] 相关文章推荐

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License

## 💡 灵感来源

- [Apple 官网](https://www.apple.com)
- [Vercel 官网](https://vercel.com)
- [OpenAI 官网](https://openai.com)
- [Tailwind CSS](https://tailwindcss.com)

---

**享受写作！** ✨
