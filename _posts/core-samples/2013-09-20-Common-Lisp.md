---
layout: post
category : lessons
tagline: "Supporting tagline"
tags : [intro, beginner, jekyll, tutorial]
---
{% include JB/setup %}

## Common Lisp 

### 安装

1.使用[lispbox](http://common-lisp.net/project/lispbox/)

2.中文编码设置

测试代码

	'你好

编码设置（emacs-23.2\site-lisp\lispbox.el）：

	(require 'slime)
	(setq slime-net-coding-system 'utf-8-unix)
