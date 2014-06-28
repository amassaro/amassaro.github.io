---
layout: post
title: From Old to Gold 
tags: [csharp webapi knockoutjs zillow]
comments: true
---

Real Estate Revival Plan

Recently I came across some old code that I wanted to showcase. Back in 2007 I had made some efforts to create a Zillow C# web service wrapper. It was working at the time yet it was never fully implemented and as such I never did anything useful with it. Fast forward to a few days ago. In matter of a minutes I was able to revive the project (yes it still ran with all the VS upgrades).

I then decided that I wanted to implement some of the cool new features of .NET using async and the headless HttpClient. I quickly duplicated all of the functionality that previously existed via async methods, refactored for a generic API caller, and mashed up a UI in an MVC project. To get the UI to talk to the Zillow services I added a WebAPI layer for data access. After all the code was in place and the syntactical sugar set I fired up the web application. Awesome! It worked.

The only thing I had left to do was to update all the XSDs from Zillow, update all the currently implemented methods, and implement the methods that I hadn't yet. After a few more hours doing this I was proud to say that I had fully implemented the Zillow APIs. I decided there after to release the C# service layer as a library on GitHub. You can find it here (https://github.com/amassaro/Zillow.Services).

If you have any questions about the code feel free fork it or provide pulls for me.