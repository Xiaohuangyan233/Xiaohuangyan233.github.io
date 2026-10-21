---
title: 快速入手MD
date: 2026-10-21
draft: false
description: 快速入手
tags: Markdown,入手,入门
---
## 1. 标题 (Headings)
使用 `#` 号表示标题，几个 `#` 就是几级标题。

# 一级标题 (H1)
## 二级标题 (H2)
### 三级标题 (H3)
#### 四级标题 (H4)

---

## 2. 文本强调 (Emphasis)
- **加粗文本**：使用两个星号 `**加粗**`
- *斜体文本*：使用一个星号 `*斜体*`
- ***加粗且斜体***：使用三个星号 `***加粗斜体***`
- ~~删除线~~：使用两个波浪号 `~~删除线~~`
- 行内代码：使用反引号 `` `code` ``
- 高亮文本：使用两个等号 `==高亮==` (注意：部分主题可能不支持)

---

## 3. 列表 (Lists)

### 无序列表 (Unordered List)
- 苹果
- 香蕉
- 橘子
  - 这是嵌套的列表
  - 还可以继续嵌套

### 有序列表 (Ordered List)
1. 打开电脑
2. 登录 GitHub
3. 开始写代码

### 任务列表 (Task List)
- [x] 搭建 Hugo 博客
- [x] 绑定 GitHub Pages
- [ ] 写 100 篇文章
- [ ] 成为大佬

---

## 4. 引用块 (Blockquote)
> 这是一个引用块。
> 可以用来引用别人的话，或者强调某段文字。
> 
> > 这是嵌套引用。

---

## 5. 代码块 (Code Blocks)
使用三个反引号加上语言名称，可以实现语法高亮。

```javascript
// 这是一段 JavaScript 代码
function sayHello(name) {
  console.log(`Hello, ${name}!`);
}
sayHello('Xiaohuangyan233');