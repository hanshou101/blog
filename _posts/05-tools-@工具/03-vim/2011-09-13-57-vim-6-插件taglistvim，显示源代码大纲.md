---
layout: post
id: 57
alias: vim-6-taglist-plugin-to-show-outline
tags: IDE
date: 2011-09-13 00:07:49
title: vim 6. 插件taglist.vim，显示源代码大纲
---

所谓大纲，就是把一个源代码文件（比如java,c,c++,c#,php等等）中的类名、函数名、字段名等等提取出来显示，可以让我们快速对整个文件的结构有一个概览。
<p>vim本身没有提供这个功能，但是通过一些爱好者写的插件程序，就可以做到。比如这个好评如潮下载量惊人的插件taglist.vim。
<p>先来个图看看，使用前：
<p>[![image](/user_images/57-1.jpg "image")](/user_images/57-1.jpg)
<p>使用后：
<p>[![image](/user_images/57-3.jpg "image")](/user_images/57-3.jpg)
<p>看起来还不错吧：）
<p>taglist依赖于另一个工具叫：ctags，必须先安装它才能正常作用。ctags是一个命令行工具，它可以把几十种不同编程语言的源文件中的大纲信息提取出来，生成一个索引文件。taglist实际上是把它与vim结合在了一起。
<p>安装教程：
<p>[http://blog.csdn.net/unbutun/archive/2009/03/10/3976894.aspx](http://blog.csdn.net/unbutun/archive/2009/03/10/3976894.aspx)
<p>[http://cid-8eca0345e6c4ea28.spaces.live.com/Blog/cns!8ECA0345E6C4EA28!113.entry](http://cid-8eca0345e6c4ea28.spaces.live.com/Blog/cns!8ECA0345E6C4EA28!113.entry)
<p>taglist主页：[http://vim-taglist.sourceforge.net/](http://vim-taglist.sourceforge.net/)
<p>ctags主页：[http://ctags.sourceforge.net/](http://ctags.sourceforge.net/)
