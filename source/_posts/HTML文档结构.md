---
title: HTML文档结构
date: 2022-02-07 15:42:33
tags:
---
最简单的html文档结构如下：
````
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>文档标题</title>
  </head>
  <body>
    <div id="app"></div>
  </body>
</html>
````

其中：
- `<!DOCTYPE html>`标记了文档类型。早期的DOCTYPE用来标记一些html编写规范，现今基本使用html5，仅使用`<!DOCTYPE html>`保证文档正确读取，其他知识点不再需要。
- `<html></html>`是根元素
- `<head></head>`可以理解为本文件的配置文件，包含meta、title、link等标签，声明了面向搜索引擎的搜索关键字、css文件、编码声明等。
- `<meta charset="utf-8">`指定文档使用utf-8编码，该编码已经包括绝大多数人类语言的字符，已没有必要使用其他编码。
- `<title></title>`页面标题，显示在浏览器标签页上。
- `<body></body>`body元素，包含所有希望用户看到的内容，包括文本、图像、视频等。






