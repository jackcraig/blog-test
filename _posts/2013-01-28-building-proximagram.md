---
layout: post
title: Building Proximagram
tags:
---

![image](http://38.media.tumblr.com/ef96b8abfcc10e312d7329af67931a65/tumblr_inline_mh1non8Nxl1qcf6rf.jpg)

[Proximagram](http://www.proximagram.com) is a small web app I’ve created using the Instagram API and the HTML 5 Geolocation API. It uses geolocation to access your position and then returns photos taken nearby on Instagram. It’s great for gigs, sport events and snooping on other people’s dinners at restaurants. Other Instagram location based search tools exist but I wanted to create one that was quick, web-based and mobile friendly. It’s purposely not as comprehensive as other tools. It does one job. Quickly and easily. No gimmicks.

I’ve designed it primarily for mobile but I’ve built it using a fluid layout so it will look ok on desktop as well. The design is still pretty raw in places but I thought it was just important to get it out there! It’s a pet project so I will tinker away at it whenever I get a chance. 

![](http://33.media.tumblr.com/04d53045fd54d04ba47096abd32e7329/tumblr_inline_muz31vlwP91qcf6rf.jpg)

![image](http://38.media.tumblr.com/adf91d4e936ce42f83f5e09953b491a7/tumblr_inline_mukimmHhhb1qcf6rf.jpg)

Unfortunately there are a few snags…

1.  Instagram has a 5000 request limit per hour for their API. You can get around this by requiring users to login - but that would kill the ease of the one click search* so I’ve got no interest in doing that at the moment. It is what it is.
2.  Most people don’t check that their photos have been tagged in the correct place (this is different to the Four Square tagging). So you may well get holiday snaps from Barbados whilst your in Bermondsey! Oh well… 
3.  It’s a side project. It hasn’t been fully tested. A trip to the testing studio <small>_(phone shop)_</small> is needed. 

It’s my first attempt at tinkering with an API so I’ve kept it simple. I’ve got a few minor advancements I still want to add but it’s not intended to be a fully featured Instagram search tool. Any thoughts send them to [@jackcraig](http://www.twitter.com/jackcraig).

_*ok two clicks including giving the browser access to your location ;)_