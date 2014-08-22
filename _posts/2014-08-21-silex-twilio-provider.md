---
layout: post
title: Building bridges one brick at a time
tags: [php silex twilio]
comments: true
---

Learning new frameworks is fun for those of us that, well, love what we do. And on that note Silex is no different. Getting back in the PHP game is also fun. It helps me get my mind away from the .NET daily grind and get back to where it all started for me. Needless to say some of these new php coding styles and patterns take some getting used to, but admittedly I like it.

So a while ago I threw together a small app in Silex. It was pretty simple. Receive call flow from [Twilio](http://www.twilio.com) using their PHP API and inform Twilio to play and record a message. Twilio API is pretty awesome, it allows for callbacks to your application when certain actions are complete. In this case, when a call is finished recording, return that URL to my application so I can download it and email it as an attachment.

With the desire to learn more about [Silex](http://silex.sensiolabs.org) and [Packagist](https://packagist.org) for that matter, I decided that I would start using GitHub more and make the package available to the public.

The source can be found here [https://github.com/amassaro/silex-twilio-provider] and the packagist info here [https://packagist.org/packages/amassaro/silex-twilio-provider].