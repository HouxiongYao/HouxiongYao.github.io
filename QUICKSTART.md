# 🎨 科技风 Jekyll 博客 - 快速使用指南

## 🚀 立即查看效果

```bash
# 启动本地服务器
bundle exec jekyll serve

# 访问
open http://localhost:4000
```

## 📁 项目结构说明

```
blog/
├── _includes/              # 可复用组件
│   ├── head.html          # 网页头部（字体、样式）
│   ├── header.html        # 顶部导航栏
│   ├── footer.html        # 底部页脚
│   └── mathjax.html       # 数学公式支持
│
├── _layouts/              # 页面布局模板
│   ├── default.html       # 基础布局（背景特效）
│   ├── home.html          # 首页（博客列表）
│   ├── post.html          # 文章页
│   └── page.html          # 普通页面
│
├── assets/css/            # 样式文件
│   └── custom.css         # 自定义CSS
│
├── _posts/                # 博客文章目录
│   ├── 2025-11-03-theme-showcase.md
│   └── 2025-11-03-math-formula-example.md
│
├── _config.yml            # Jekyll 配置文件
├── index.markdown         # 首页
├── about.markdown         # 关于页面
└── 404.html              # 404 错误页面
```

## ✍️ 如何写文章

### 1. 创建新文章

在 `_posts/` 目录下创建文件：

```bash
touch _posts/2025-11-03-my-new-post.md
```

### 2. 文章模板

```markdown
---
layout: post
title: "你的文章标题"
date: 2025-11-03 15:00:00 +0800
categories: 技术
tags: [标签1, 标签2, 标签3]
---

# 这是一级标题

这是正文内容...

## 这是二级标题

更多内容...
```

### 3. 常用语法

**加粗文本**
```markdown
**这是粗体**
```

**斜体文本**
```markdown
*这是斜体*
```

**代码块**
````markdown
```python
def hello():
    print("Hello!")
```
````

**行内公式**
```markdown
这是公式 $E = mc^2$ 在文本中
```

**独立公式**
```markdown
$$
\frac{a}{b} = c
$$
```

**插入图片**
```markdown
![图片描述](图片URL)
```

**插入链接**
```markdown
[链接文字](https://example.com)
```

## 🎨 自定义设置

### 修改网站信息

编辑 `_config.yml`：

```yaml
title: 你的博客名称
email: your-email@example.com
description: 博客简介
url: "https://yourusername.github.io"
github_username: yourusername
```

### 修改导航栏

编辑 `_includes/header.html`，找到导航链接部分：

```html
<a href="{{ '/' | relative_url }}">首页</a>
<a href="{{ '/about' | relative_url }}">关于</a>
<!-- 添加更多链接 -->
```

### 修改主题色

编辑 `_includes/head.html`，在 Tailwind 配置中：

```javascript
colors: {
  'tech-cyan': '#06b6d4',    // 改成你喜欢的颜色
  'tech-purple': '#8b5cf6',  // 改成你喜欢的颜色
}
```

## 🎯 关键功能

### ✅ 已实现

- ✨ 现代科技风设计
- 📱 完全响应式布局
- 🔍 搜索界面（待集成搜索引擎）
- 📐 数学公式支持
- 💻 代码高亮
- 🎨 流畅动画效果
- 🔝 返回顶部按钮
- 🔗 文章分享功能
- 📄 上一篇/下一篇导航

### 🚧 可扩展

1. **搜索功能** - 可集成：
   - Algolia Search
   - Lunr.js
   - Simple Jekyll Search

2. **评论系统** - 可集成：
   - Disqus
   - Giscus (GitHub Discussions)
   - Utterances (GitHub Issues)

3. **分析工具** - 可集成：
   - Google Analytics
   - Cloudflare Analytics

## 📱 响应式测试

在浏览器开发者工具中测试不同设备：

- iPhone SE (375px)
- iPad (768px)
- Desktop (1920px)

## 🔧 常见问题

### Q: 本地预览时样式正常，但部署后样式丢失？

A: 检查 `_config.yml` 中的 `baseurl` 和 `url` 设置是否正确。

### Q: 数学公式不显示？

A: 确保 `_includes/mathjax.html` 已被正确引入到布局文件中。

### Q: 如何添加新页面？

A: 在根目录创建 `.md` 或 `.html` 文件，使用 `layout: page`。

### Q: 如何修改字体？

A: 在 `_includes/head.html` 中修改 Google Fonts 链接。

## 🚀 部署到 GitHub Pages

```bash
# 1. 确保代码已提交
git add .
git commit -m "Update blog theme"

# 2. 推送到 GitHub
git push origin main

# 3. 在 GitHub 仓库设置中启用 Pages
# Settings > Pages > Source: main branch
```

## 📚 推荐学习资源

- [Jekyll 官方文档](https://jekyllrb.com/)
- [Tailwind CSS 文档](https://tailwindcss.com/)
- [MathJax 文档](https://www.mathjax.org/)
- [Markdown 语法指南](https://www.markdownguide.org/)

## 💡 写作建议

1. **保持简洁** - 避免过长的段落
2. **使用标题** - 合理组织文章结构
3. **添加代码** - 技术文章配合代码示例
4. **插入图片** - 适当使用可视化内容
5. **检查链接** - 确保所有链接有效
6. **预览效果** - 发布前先本地预览

## 🎉 开始写作

一切就绪！现在你可以：

1. 📝 创建新文章
2. 🎨 自定义主题
3. 🚀 发布博客
4. 📊 分享内容

**享受写作的乐趣！** ✨

---

如有问题，请参考 `THEME_README.md` 获取完整文档。
