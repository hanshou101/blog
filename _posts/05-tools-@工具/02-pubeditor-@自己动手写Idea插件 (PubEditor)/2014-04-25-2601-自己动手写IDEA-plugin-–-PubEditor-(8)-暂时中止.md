---
layout: post
id: 2601
alias: write-idea-plugin-yourself-pubeditor-8-pause-dev
tags: 未分类
date: 2014-04-25 23:13:06
title: 自己动手写IDEA plugin – PubEditor (8) 暂时中止
---

这个系列到这里就暂时中止了。

因为我发现，想要实现更多的功能，比如代码提示、格式化这些看起来似乎不太复杂的，都需要我们在Lexer的基础上提供一个Parser，以及相应的PsiElement等，在它们的基础上继续开发。

但IDEA中相关的API很庞大，类很多、代码很多，因为它们需要为编辑器提供强大的编辑、查找、重构、定制等功能，而文档和资料又比较少，只能从代码去猜，不是短时间内能掌握的。

所以我打算暂时中止，转而以研究IDEA代码为主，然后再回过头来继续实现该插件。
