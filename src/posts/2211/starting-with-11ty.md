---
title: Starting Out With Eleventy (11ty) CRM & Why Duplication Sucks
date: 2022-11-14
tags:
  - posts
layout: layouts/post.njk
---

Eleventy is fairly easy if you know javascript.  It seems to be very 
customisable and almost like any db based CMS except you don't need a db!

### The major stumbling block was duplication in the starter project.

The starter project had two pages with duplicate code.  
Duplicate code is not looked at favourably at the best of times (maintenance, readability of code, reuse etc).  

Today, I saw the same piece of code, changed it, it didn't do anything and I didn't know why it wasn't changing.  However the code was duplicated and the code I was changing wasn't the code that I was loading up - duplication sucks! (also my attention to detail!)

This doesn't sound so difficult but when I am faced with new technology I often think it is the fact I've got something more fundamentally wrong.

### glitch.com

Glitch is in theory a nice little website that hosts your data for you.  However I found it to be slow to update the more I used it.  Possibly they favour paid for customers but the slowness put me off buying it (to be fair I probably wouldn't have bought it anyway!)

### Summary

Instead I ran the setup locally and everything else was a breeze really.

