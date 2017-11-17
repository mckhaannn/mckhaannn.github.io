---
layout: post
comments: true
title:  "pre-compiling CSS"
date:   2017-11-15 10:46:10 +0100
categories: jekyll update
---

### What do you think of pre-compiling your CSS?

To pre-compile your CSS you need a preprocessorrs like Sass takes code  that is written in scss and convrts it to normal CSS.  
I think that pre-compling is a very efficiant way to write CSS code because it offers more functions than normal CSS like, nestin, mixins and varibales etc. However in the end the code works just fine in any browser.  
After using pre-compiling processors I really like it because it have spared me repeating the code.

#### Compare to regular CSS

To compare the both you save a lot of time doing pre-compiling your CSS because you can avoid repeating your code (DRY) with variables that you can apply on elements of your choice, these varibales can for example hold colors, font-size, font-style etc. pre-compiling also notifies you if you use a variable that you havent declared. So by using pre-compiling CSS you can maintain your code much easiler and effective.

#### Which techniques have you used?

I have tried some techniques for an example I have used variables for my colors and for some opacity for some parts of the site and I really like to use it!

#### Pros and cons?

The pros of using pre-compiling CSS is that it's efficient and very timesaving and it makes you reuse the code you have written and sustain the DRY principle. Cons with using pre-compiling CSS is that debugging code can come with some problems because when you are coding with pre-compilin the code line dosen't  match the CSS code in the browser. But there is a fix for that, sorce mapping, that is a .map which is a format that shows you the corresponding scss line to CSS.