---
title: html页面强制所有链接新窗口打开的代码
date: 2020-07-13
categories:
- 默认分类
tags:
- Html
---

> html页面强制所有链接新窗口打开的代码

<!-- more -->

```html
<base target="_blank">
```

>> 将此上/下（二选一）代码放到网页中的 <head>标签之内即可实现,  
>> 当前页面所有链接新窗口打开  

```html
<base target="_self">
```
**<base> 标签使用注意事项**
* 1、一个页面中，<base> 标签只能出现一次
* 2、<base> 标签只能在 <head></head>标签中出现
* 3、<base> 属于单标签，没有结束标签，类似 <img> 标签
