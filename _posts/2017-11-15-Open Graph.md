---
layout: post
comments: true
title:  "What is Open Graph?"
date:   2017-11-15 10:46:10 +0100
categories: jekyll update
---

### What is Open Graph and how do you make us of it?

By using Open Graph Protocol, it makes it possible to have control over how your website is represented when shared in social media.
To implement Open Graph on your site you must add Meta Tags in the head section. I have created a new file called **opengraph.html** and implemented it in **head.html** with an if statement which is possible with Jekyll, by doing this Open Graph gets dynamic and available over the website.  
The Meta Tags I have been using is


```
<title>Marcus Thuresson's Website</title>
<meta property="og:title" content="Tmack" />
<meta property="og:type" content="website" />
<meta property="og:url" content="https://mckhaannn.github.io/" />
<meta property="og:image" content="https://mckhaannn.github.io/img/bild2.jpg" />
```