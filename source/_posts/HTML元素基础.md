---
title: HTML元素基础
date: 2022-02-07 15:51:48
tags:
---
### 块级元素和行内元素
`块级元素`总是会重新占据一行，之后的元素也会被挤到下一行，常见的块级元素有div、p、h1~h6、header、footer等

`行内元素`只占据可以占据的最小空间，之后的元素紧跟在其右侧，常见的行内元素有span、a、input、select、img等

### html中的空格
html默认将多个空格、tab显示为一个空格
如果要显示多个空格，可以使用：
1、pre标签
2、css属性white-space: pre
3、多个&nbsp;


### html中的特殊字符
html中的<, >,",' 和 & 是特殊字符，需要转义后使用：

| 原义字符 | 等价字符引用 |
| ----- | ----- |
| `<` | `&lt;`|
| `>` | `&gt;` |
| `"` | `&quot;` |
| `'` | `&apos;` |
| `&` | `&amp;` |
