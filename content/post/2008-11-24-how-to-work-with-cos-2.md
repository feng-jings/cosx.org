---
title: 用户如何参加“统计之都”网站的各项工作
date: '2008-11-24T22:53:39+00:00'
author: COS管理员
categories:
  - 新闻通知
tags:
  - 主站
  - 博客
  - 审稿
  - 工作
  - 投稿
  - 用户
  - 申请
  - 论坛
slug: how-to-work-with-cos-2
---

“统计之都”（COS）网站是一个协作平台，它是在群体合作的基础上而发展起来的。本文对参加COS网站工作的方式给予以下说明<!--more-->：

# 申请事宜

统计之都除了论坛之外，一律需要申请注册（我们不提供开放注册）。有意成为COS主站文章作者或COS论坛版主的朋友，请发送您的简历或自我介绍至邮箱**editor@cos.name**；对于主站作者，请在邮件中注明您预期得到的用户名，**并附带您准备在COS主站上发表的首篇文章**。稿件被采纳后，请作者在文章发表之前提供一段个人简介，这个信息将显示在文章开头，便于读者更多了解作者并知道在有疑问或其它事宜时如何联系作者。

## 特别说明

  * COS网站的两大组成部分（主站和论坛）相对独立，各站用户名不能通用，申请时请注明您申请的职位。

# COS主站

COS主站主要为群体博客形式，其团队由多位投稿者、作者和编辑组成。以下分别对投稿要求及成为长期撰稿人进行说明。

## 投稿要求

对于投稿文章，统计之都将安排专业相关人员进行审稿并择优录用。文章内容建议涵盖但不限于：

  * 产业相关数据实践
  * 编程语言/工具介绍及应用
  * 统计、机器学习建模科普及实践

……（内容可参考统计之都已发表文章）

为了提高文章的可读性、趣味性，审稿人将与您进一步沟通并提出反馈意见。最终修改成文稿件将在统计之都平台（主站+微信）公开发表。

若您不想成为COS主站成员，那么仍然可以以邮件或其它方式向我们推荐稿件，需要注意的是请您在推荐之前协助解决作者授权问题，本站不发布未经授权的文章。

## 成为长期撰稿人

对于长期撰稿人，经COS编辑部审核后，我们将为您建立COS主站[个人档案](https://uploads.cosx.org/wp-admin/profile.php)^[该链接已失效]。您可以通过后台向COS主站投稿，稿件需经过审稿流程，经编辑批准才能发布。本站后台为Wordpress，界面如下：![COS后台文章编辑器](https://uploads.cosx.org/2008/11/editor-for-authors.png)

### **写作注意事项：**

  1. 链接：作者编写文章时注意设置合理的**永久链接**，本站所有页面的永久链接形式为“域名/年份/月份/**标题英文单词用减号连接**”，写文章时注意编辑、更改这个地址；
  2. 图形：对于**以图形为主题**的文章，正文中的图形一般设置**居中对齐**，图形宽度一般**不超过600像素**，若原图形非常大，那么可以插入其**合适大小的缩略图**；上传图形文件的文件名最好**用有意义的名称**如econometrics-intro.png，而不要采用1.png、2.png之类的文件名；每一幅图形请给出图形的**说明文字和标题**；不推荐在本站发布截图类文章（例如软件教程），原因是此类文章图片数量太多，而HTML页面本身不适合排版，建议作者给出文章摘要之后直接使用PDF文档上传；
  3. 数学公式：LaTeX数学公式可以放在[**latex**][/**latex**]标签中，如[**latex**]\bar{x}=\frac{1}{n}\sum x_i[/**latex**]会被转化为`\(\bar{x}=\frac{1}{n}\sum x_i\)`；
  4. 关键词：编辑文章的时候“标签”即该文的关键词，请用**英文逗号**分开各个关键词；
  5. HTML规范：为了文章的可读性，请在撰写文章时尽量使用整洁规范的HTML标签，例如每个段落都用`<p></p>`标签，而不用`<br/ >`强制空行；
  6. 代码：程序代码放在“预格式化”环境中，即HTML的`<pre></pre>`标签内；很多统计分析输出都支持纯文本格式，因此统计表格可以使用预格式化环境发布，避免直接使用超宽的表格导致混乱的排版；使用预格式化环境之前，请[先到这里将HTML特殊字符进行编码](http://www.functions-online.com/htmlspecialchars.html)（把文本粘贴到`$str`的文本框中，然后底下`$charset`选择UTF-8，最后点run按钮，复制生成的结果），在主站后台编辑器中切换到HTML代码视图（见上图），在合适位置粘贴编码过的文本，并在其前后分别加上`<pre>`和`</pre>`标签；主站支持若干程序语言的高亮：R、SQL、JavaScript和HTML/XML，若要使用代码高亮，请为pre标签加上class属性，例如`<pre class="brush: r">`，这里brush后面可以取的值有`r, sql, js, html, xml, plain`，其中`plain`为普通代码（可以是任意语言）；如

```html
<pre class="brush: r">
  x <- hist(rnorm(30))  # 直方图
  x$mids # 直方图横坐标中点
</pre>
```    
将生成：
```r
x <- hist(rnorm(30))  # 直方图
x$mids  # 直方图横坐标中点
```
这样的代码读者可以通过双击实现全选，然后自行复制。

* 附件：允许的附件类型参见[WordPress附件说明](http://codex.wordpress.org/User:Lolrus/Using_Attachments#Appendix:_Allowed_attachment_file_types "允许的附件类型")，由于支持gz、zip等压缩文件，因此理论上任意文件都可以通过压缩的方式发布，但由于网站空间有限，如无必要，请各位作者不要上传大量附件（可以将文件上传至专门的文件共享网站或者打包压缩为gzip或zip格式）；

# COS论坛

COS论坛主要用于会员的讨论与交流，论坛涵盖学科分支广泛，因此我们需要一批对特定学科感兴趣并且有足够业余时间来关心论坛发展的朋友担任版主，协调版面工作。

# 捐赠计划

“统计之都”接收社会捐赠，详情参见：[https://cos.name/donate/](https://cos.name/donate/ "为统计之都捐赠")
