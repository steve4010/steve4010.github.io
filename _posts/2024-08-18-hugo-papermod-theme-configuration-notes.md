---
layout: post
title: "Hugo PaperMod Theme Configuration Notes"
date: 2024-08-18
---

I installed the PaperMod theme on Hugo.

These are random notes on settings, etc.

## Tags and Categories in Posts

I had seen some examples of laying out the array like this: 
```sh
tags: [ tag1, tag2, etc ]
```

I might have been doing it wrong but I couldn't get it to work like that.

Below is what worked for me.

The post tags and categories array in the post front matter:

```sh
tags:
- tag1
- tag2
 
categories:
- category1
- category2
```
**Update**

I got the code below to work.  After some reading, I found I had spaces inside the brackets that was causing it not to work.
both versions worked but, I like the example below, it looks neater.

```sh
tags: [tag1, tag2, tag3]
category: [cat1, cat2]
```




