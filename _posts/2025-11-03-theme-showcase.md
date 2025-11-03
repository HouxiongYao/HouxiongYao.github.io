---
layout: post
title: "主题演示 - 所有功能展示"
date: 2025-11-03 14:00:00 +0800
categories: 演示
tags: [设计, 功能, 示例]
---

# 欢迎使用科技风主题！

这篇文章将展示本主题的所有功能和样式效果。

## 📝 文本样式

这是一段普通文本。你可以使用 **粗体文本** 和 *斜体文本* 来强调重要内容。还可以使用 ~~删除线~~ 来表示已删除的内容。

### 引用块

> 这是一段引用文本。引用块使用了渐变边框和半透明背景，让内容更加突出。
> 
> 适合用来引用他人的话语或重要的提示信息。

### 代码展示

行内代码：`const greeting = "Hello, World!";`

代码块示例：

```javascript
// JavaScript 示例
function calculateFactorial(n) {
  if (n <= 1) return 1;
  return n * calculateFactorial(n - 1);
}

const result = calculateFactorial(5);
console.log(`5! = ${result}`); // 输出: 5! = 120
```

```python
# Python 示例
def fibonacci(n):
    """计算斐波那契数列的第 n 项"""
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

# 生成前 10 项
fib_sequence = [fibonacci(i) for i in range(10)]
print(f"斐波那契数列: {fib_sequence}")
```

## 📊 数学公式

### 行内公式

质能方程 $E = mc^2$ 是物理学中最著名的公式之一。

勾股定理：在直角三角形中，$a^2 + b^2 = c^2$。

### 独立公式

**二次方程求根公式：**

$$
x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
$$

**欧拉公式（数学中最美的公式）：**

$$
e^{i\pi} + 1 = 0
$$

**矩阵表示：**

$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
\begin{bmatrix}
x \\
y
\end{bmatrix}
=
\begin{bmatrix}
ax + by \\
cx + dy
\end{bmatrix}
$$

**求和与积分：**

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2} \quad \text{和} \quad \int_{0}^{\infty} e^{-x} dx = 1
$$

**麦克斯韦方程组：**

$$
\begin{aligned}
\nabla \cdot \vec{E} &= \frac{\rho}{\epsilon_0} \\
\nabla \cdot \vec{B} &= 0 \\
\nabla \times \vec{E} &= -\frac{\partial \vec{B}}{\partial t} \\
\nabla \times \vec{B} &= \mu_0\vec{J} + \mu_0\epsilon_0\frac{\partial \vec{E}}{\partial t}
\end{aligned}
$$

## 📋 列表

### 无序列表

- 第一项
- 第二项
  - 嵌套项 2.1
  - 嵌套项 2.2
    - 更深层嵌套
- 第三项

### 有序列表

1. 首先做这个
2. 然后做那个
3. 最后完成
   1. 子步骤 A
   2. 子步骤 B

### 任务列表

- [x] 已完成的任务
- [x] 另一个已完成的任务
- [ ] 待完成的任务
- [ ] 另一个待完成的任务

## 📊 表格

| 功能 | 状态 | 优先级 |
|------|------|--------|
| 响应式设计 | ✅ 完成 | 高 |
| 暗色主题 | ✅ 完成 | 高 |
| 数学公式 | ✅ 完成 | 中 |
| 搜索功能 | 🚧 进行中 | 中 |
| 评论系统 | 📋 计划中 | 低 |

## 🔗 链接

这是一个 [外部链接](https://www.google.com) 示例。

这是一个 [内部链接]({{ '/' | relative_url }}) 返回首页。

## 🖼️ 图片

图片会自动居中，并添加圆角和阴影效果。悬停时会有轻微的放大效果。

![示例图片](https://via.placeholder.com/800x400/0a0e17/06b6d4?text=科技风博客主题)

*图片说明：这里是图片的描述文字*

## 📐 分隔线

---

上面是一条分隔线，使用渐变效果。

---

## 🎨 特殊效果

### 高亮文本

使用 `<mark>` 标签可以<mark style="background: rgba(6, 182, 212, 0.2); color: #06b6d4; padding: 2px 4px; border-radius: 4px;">高亮重要内容</mark>。

### 键盘按键

按下 <kbd style="background: rgba(255, 255, 255, 0.1); padding: 2px 8px; border-radius: 4px; border: 1px solid rgba(255, 255, 255, 0.2); font-family: monospace;">Ctrl</kbd> + <kbd style="background: rgba(255, 255, 255, 0.1); padding: 2px 8px; border-radius: 4px; border: 1px solid rgba(255, 255, 255, 0.2); font-family: monospace;">C</kbd> 复制内容。

## 💡 提示框

你可以使用 HTML 来创建自定义的提示框：

<div style="padding: 1rem 1.5rem; margin: 1.5rem 0; border-left: 4px solid #06b6d4; background: rgba(6, 182, 212, 0.1); border-radius: 0 0.5rem 0.5rem 0;">
  <strong>💡 提示：</strong> 这是一个信息提示框，用于显示有用的提示信息。
</div>

<div style="padding: 1rem 1.5rem; margin: 1.5rem 0; border-left: 4px solid #8b5cf6; background: rgba(139, 92, 246, 0.1); border-radius: 0 0.5rem 0.5rem 0;">
  <strong>⚠️ 警告：</strong> 这是一个警告提示框，用于显示需要注意的信息。
</div>

<div style="padding: 1rem 1.5rem; margin: 1.5rem 0; border-left: 4px solid #10b981; background: rgba(16, 185, 129, 0.1); border-radius: 0 0.5rem 0.5rem 0;">
  <strong>✅ 成功：</strong> 这是一个成功提示框，用于显示操作成功的信息。
</div>

## 🎯 技术栈展示

<div style="display: flex; flex-wrap: wrap; gap: 0.5rem; margin: 1.5rem 0;">
  <span style="padding: 0.5rem 1rem; background: rgba(6, 182, 212, 0.2); color: #06b6d4; border-radius: 9999px; font-size: 0.875rem; font-weight: 500;">Jekyll</span>
  <span style="padding: 0.5rem 1rem; background: rgba(6, 182, 212, 0.2); color: #06b6d4; border-radius: 9999px; font-size: 0.875rem; font-weight: 500;">Tailwind CSS</span>
  <span style="padding: 0.5rem 1rem; background: rgba(6, 182, 212, 0.2); color: #06b6d4; border-radius: 9999px; font-size: 0.875rem; font-weight: 500;">MathJax</span>
  <span style="padding: 0.5rem 1rem; background: rgba(139, 92, 246, 0.2); color: #8b5cf6; border-radius: 9999px; font-size: 0.875rem; font-weight: 500;">JavaScript</span>
  <span style="padding: 0.5rem 1rem; background: rgba(139, 92, 246, 0.2); color: #8b5cf6; border-radius: 9999px; font-size: 0.875rem; font-weight: 500;">HTML5</span>
  <span style="padding: 0.5rem 1rem; background: rgba(139, 92, 246, 0.2); color: #8b5cf6; border-radius: 9999px; font-size: 0.875rem; font-weight: 500;">CSS3</span>
</div>

## 📱 响应式设计

本主题完全支持响应式设计，在不同设备上都能获得最佳体验：

- 📱 **手机端**：< 768px
- 💻 **平板端**：768px - 1024px
- 🖥️ **桌面端**：> 1024px

## 🎉 总结

这个主题包含了现代博客所需的所有功能：

✅ 优雅的深色主题  
✅ 流畅的动画效果  
✅ 完整的数学公式支持  
✅ 响应式设计  
✅ 代码高亮  
✅ 搜索功能  
✅ 社交分享  

希望你喜欢这个主题！开始写作吧！ 🚀

---

**最后更新时间：** {{ page.date | date: "%Y年%m月%d日" }}
