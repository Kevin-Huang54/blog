---
title: HTML头部元素
date: 2022-02-07 16:42:10
tags:
---
HTML的header元素中放置了页面的配置信息，包括以下：
### meta标签
元信息标签，主要应用有以下几种
- `<meta charset="utf-8">`字符编码
- `<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">`IE兼容配置
- `<meta name="renderer" content="webkit">`默认web内核配置，对于双核浏览器，默认使用webkit，而不是ie兼容模式。

### link标签
- `<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">`， 配置标签页、书签栏中显示的图标
在现代浏览器中可以使用png等其他格式，使用ico文件可以保证在ie6这种古老的浏览器中显示。
- `<link rel="stylesheet" href="my-css-file.css">`引入css，vue会把打包后的css在这里引入。

### script标签
- `<script src="my-js-file.js"></script>`引入js脚本，vue会把打包后的js在这里引入。
