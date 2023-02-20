---
title: Starting Out With Eleventy (11ty) CRM & Why Duplication Sucks
date: 2022-11-14
summary: none
tags:
  - posts
layout: layouts/post.njk
---

Eleventy is fairly easy if you know javascript.  It seems to be customisable and almost like any db based CMS except you don't need a db!
I looked at Hugo and Jekyll as a static site generator.  I went with Eleventy due to its modularity and simple design; I can use all the
javascript / css / html I like.

### The major stumbling blooper - duplication in the starter project.

The starter project had two pages with duplicate code.  This was the starter project's fault, not 11ty.
Duplicate code is not looked at favourably at the best of times (maintenance, readability of code, reuse etc).  

Today, I saw the same piece of code, changed it, it didn't do anything and I didn't know why it wasn't changing.  However the code was duplicated and the code I was changing wasn't the code that I was loading up - duplication sucks! (also my attention to detail!)

This doesn't sound so difficult but when I am faced with new technology I often think it is the fact I've got something more fundamentally wrong.

### glitch.com

Glitch is in theory a nice little website that hosts your code / website for you.  However I found it to be slow to update the more I used it.
Possibly they favour paid for service is faster but I don't know.

### Summary

Instead of using glitch.com to test my site, I ran the setup locally which was a breeze.

