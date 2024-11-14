# Introduction

这里是有关网页搭建的说明，哪天忘了怎么搭建来这里看看，记得点code模式。<br>
[leap-day网页风格源代码](https://github.com/pages-themes/leap-day)

# Basic information of the website:https://fishsix20236356.github.io/

* 基于Jekyll静态站点生成器
* 如果要新建网页，在Fishsix20236356.github.io下 新建xxx.md 然后链接格式[链接名字写这里哦]（./xxx.html）

# markdown(Jekyll part,like index.md) help document

## 1.黑色文本框
```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

## 2.代码框（在'''后面加编程语言类型）

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

## 3.标题和正文

### 方法1：
#Header 1

##Header 2

###Header 3

#和head用空格隔开

### 方法2：
<dl>
<dt>Color</dt>
<dd>Green</dd>
</dl>
结果：
Color(标题)
Green(正文)

## 4.列表和子列表格式

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item

* 第一项
* 第二项

- [ ] 写报告
- [x] 回复邮件
- [ ] 准备会议资料

1. 打开冰箱
2. 放入新鲜蔬菜
3. 关闭冰箱

## 5.图片：
![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

## 6.分割线：
* * *

## 7.注释：
方法1：> 这是一段引用，它会被渲染，但通常会被样式化以区别于正文。
方法2：(已经被聪明的我注释掉啦哈哈哈)<!-- 这是一段注释，它不会在渲染的HTML中显示 -->

---
>layout: default
title: "我的页面标题"
description: "这是我的页面描述，用于SEO和页面概览。"
---

以下是对上面markdown文本的解释：
layout: 指定页面使用的布局模板。这里填写的是default，这意味着您有一个名为default.html的布局文件在 _layouts 目录中。
title: 页面的标题，这将在浏览器的标签页中显示。
description: 页面的描述，这对于SEO和页面内容的概览很有帮助。


