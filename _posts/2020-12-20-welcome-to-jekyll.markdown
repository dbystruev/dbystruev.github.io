---
layout: post
title:  "Welcome to Go Swift!"
date:   2020-12-20 22:00:00 +0300
categories: go swift
---
[goSwift.org](https://goswift.org) is going to be dedicated to using [Swift](https://swift.org) and [Go](https://golang.org) programming languages on client and server sides respectively.

Many iOS clients are written in Swift, including the one from [Get Outift](https://github.com/dbystruev/Outfit-Selection.git).

Initially [Get Outfit Server](https://github.com/dbystruev/Get-Outfit-Server.git) was using Swift as well, thanks to the great [Kitura](https://www.kitura.dev) framework. Unfortunately, after IBM [has stopped](https://forums.swift.org/t/december-12th-2019/31735) its Swift support in December of 2019, the framework was not developing as fast as [it should](https://vapor.codes).

However re-writing the server part from one Swift framework to another is not fun. Swift is a great language, but so far it had limited support from serverless platforms, though Apple did manage to persuade Amazon to run [Swift on AWS Lambda](https://developer.apple.com/videos/play/wwdc2020/10644).

Probably this is a good opportunity to try something new. The learning path so far is the following:

* A Tour of Go at [tour.golang.org](http://tour.golang.org)
* A Hands-On RESTful Web Services with Go [book by Naren Yellavula](https://www.packtpub.com/product/hands-on-restful-web-services-with-go-second-edition/9781838643577)

The idea is to re-write the [Get Outfit](https://www.getoutfit.ru/uk) Server with Go and run it on AWS Lambda. There is some $50 credit from an old hackaton which should be enough to try.

Let's Go!