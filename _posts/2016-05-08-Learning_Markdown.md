---
layout:     post
title:      "Learning_Markdown"
subtitle:   " \"Markdown学习\""
date:       2016-05-08 12:00:00
author:     "Guang"
header-img: "img/post-bg-2015.jpg"
tags:
    - interest
    - learning
---


### **Markdown学习**

#### **如何添加图片：**

{% highlight c %}
![dian.png](/img/in-post/dian.png "点")
{% endhighlight %}

![dian.png](/img/in-post/dian.png "点")

![1280px-Markdown-mark.svg.png](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1280px-Markdown-mark.svg.png "Markdown")

#### **什么是Markdown？**

我们可以参看下[Wiki](https://zh.wikipedia.org/wiki/Markdown "Markdown")。  
简而言之，Markdown就是一种为了简化工作的轻量级标记语言。而易读、简化对于我们写文则再合适不过。

### 简记Markdown常用标记

#### **段落与换行**

Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。  
类 Setext 形式是用底线的形式，利用 = （最高阶标题）和 - （第二阶标题）    
例如：

This is an H1
=============

This is an H2
-------------

任何数量的 = 和 - 都可以有效果。  
类 Atx 形式则是在行首插入 1 到 6 个 # ，对应到标题 1 到 6 阶  
例如：

# 这是 H1

## 这是 H2

### 这是 H3

#### 这是 H4

##### 这是 H5

###### 这是 H6

#### 区块引用

Markdown 标记区块引用是使用类似 email 中用 > 的引用方式。如果你还熟悉在 email 信件中的引言部分，你  
就知道怎么在 Markdown 文件中建立一个区块引用，那会看起来像是你自己先断好行，然后在每行的最前面加上 > ：  

> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

#### **列表**

Markdown 支持有序列表和无序列表。      
无序列表使用星号、加号或是减号作为列表标记：    

* Green
* Blue

其中， * 也可以替换成 + 或者 - 。  

#### **链接**

Markdown 支持两种形式的链接语法： 行内式和参考式两种形式。  
不管是哪一种，链接文字都是用 [方括号] 来标记。  
要建立一个行内式的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只  
要在网址后面，用双引号把 title 文字包起来即可，例如：   

> This is [an example](http://example.com/ "Title") inline link.
> [This link](http://example.net/) has no title attribute.

#### **强调**

Markdown 使用星号（*）和底线（_）作为标记强调字词的符号，被 * 或 _ 包围的字词会被转成用 em 标签包围    
用两个 * 或 _ 包起来的话，则会被转成 strong 标签，例如：    

_single underscores_

*double asterisks*

#### **图片**

很明显地，要在纯文字应用中设计一个「自然」的语法来插入图片是有一定难度的。  
Markdown 使用一种和链接很相似的语法来标记图片，同样也允许两种样式： 行内式和参考式。  
行内式的图片语法看起来像是：    

> ![Alt text](/path/to/img.jpg)
> ![Alt text](/path/to/img.jpg "Optional title")

详细叙述如下:    
+ ![图片的替代文字][图片的网址 选择性的 'title' 文字]

### **如何添加表格**


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
