---
layout: post
title: Build Free Blog Website with Github Pages and Jekyll
description: "Steps to build a free blog website by using Github Pages and Jekyll."
tags: [tutorial post]
image:
  background: triangular.png
---

Nowadays, blog is getting more and more important. More and more people start to play with blog by using various existing blog systems. Some people even try to build their own blog system by using wordpress or some other tools. Today, I will introduce you an easy way to build your own blog website by using Github Pages. 

First, Let me talk about the pros and cons of Github Pages.

* Advantages:

	* free
	* no need to establish your own web server
	* can bind to your own domain name
	* lightweight, no complex configuration

* Disadvantages:

	* it uses Jekyll template system, more suitable for posting blog, documentation and so on
	* limited dynamic web supporting
	* based on Git, there is no powerful backend like wordpress, and many work should be done manually

Then, let's come to the "how to build".

## 1. "Activate" Your Github Pages

Please refer to [official guide](https://pages.github.com/)

## 2. Prepare Jekyll Template 

Here, [**HPSTR Jekyll Theme**](https://mmistakes.github.io/hpstr-jekyll-theme/theme-setup/) is recommended.

The following is the preview of HPSTR Jekyll Theme:

![HPSTR Theme Preview screenshot](http://mmistakes.github.io/hpstr-jekyll-theme/images/hpstr-jekyll-theme-preview.jpg)

**Notice**: 

1. You need do some simple configuration of the template files, before you push them to your Github repository (i.e., username.github.io).
2. If you want preview your blog before you upload to your Github, you could [build a local Jekyll template system](http://xlong88.github.io/build-local-Jekyll/)

## 3. Push These Files onto Your Github Repository (The One You Created in Step 1)