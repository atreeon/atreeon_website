---
title: Eleventy - Adding Flutter Standalone App to Eleventy Website
date: 2023-01-13
summary: no summary
tags:
  - posts
layout: layouts/post.njk
---


### Build flutter app and set the base-href environment variable
```flutter build web --base-href /flutter_packages/```

### Copy over the flutter built web code to the root directory of Eleventy site

### Add the following line in .eleventy.js to copy the files over
```eleventyConfig.addPassthroughCopy("flutter_packages");```

### Be aware
Ensure the flutter code is in the root directory 

definitely not the 'src' because 11ty tries to process it there & copy it over...it mangles it into 11ty form which is not what we want.

nor in the build directory because everything gets overwritten in there.



