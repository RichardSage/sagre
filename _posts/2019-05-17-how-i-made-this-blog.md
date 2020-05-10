---
layout: post
title:  "How i made this blog"
author: richard
categories: [ Blog ]
image: assets/images/home.jpg
tags: featured
comments: false
---

After doing literally nothing for Two years with a Hugo blog on my sage.re domain, hosted on github pages i felt like it was time to do something different, in a way i found more usable to make it more likely for me to blog more.
After looking around at various options including Wordpress i decided to go for Jekyll, primarily because it seemed like the cheapest solution (i could host on github pages for free, or AWS for peanuts).
So the tech powering this site is really simple, just Jekyll with the Memoirs theme, S3 for hosting, Cloudfront for CDN, Route 53 for DNS and SSL
