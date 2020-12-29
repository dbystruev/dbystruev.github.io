---
layout: post
title:  "Finished a tour of Go"
date:   2020-12-29 17:00:00 +0300
categories: go
---
A [Tour of Go](http://tour.golang.org) was fun and gave a good overview of the language.

There were interesting exercises starting from loops and functions up to a web crawler.

While doing them created a small [category lister](https://github.com/dbystruev/Get-Outfit-Tools) console script as a test, which requests the full list of categories from Get Outfit server and then loops through them getting the number of items in each category one by one. Didn't want to use concurrent HTTP requests as the current non-optimized server jumps to 100% CPU usage while processing each request.

Continuing with [the book](https://www.packtpub.com/product/hands-on-restful-web-services-with-go-second-edition/9781838643577). Chapter 1 was easy, some typos made the task of repeating the [Mirror Finder](https://github.com/dbystruev/mirrorFinder) not so boring.
