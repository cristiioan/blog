---
title: Why I have analytics on my website?
date: 2022-03-01T06:18:23+02:00
slug: 2022-03-01-is-privacy-a-right
type: posts
draft: false
categories:
  - default
tags:
  - default
description: Why I decided to add analytics to my website, what I have been using and how
  much data I collect from you.
lastmod: 2022-03-03T15:44:25.004Z
---

In the last few months I began starting to increase my privacy, by limiting what I share with others and what companies can track me. I made a lot of progress, but I still have a lot to learn. This blog post was made as a way to talk about why I decided to add analytics to my website, what I have been using, how much data I collect from you, and how I block ublock from blocking my analytics scripts.

Hold on, before you leave this blog saying that it is tracking me, I want to make sure you understand what I'm doing so please read on.

### What is tracking and analytics?

Tracking and analytics are two different things. Tracking is the process of collecting data from your website and using it for making money, while analytics is the process of collecting data from your website and using it for making your website better. They are two different things, but they are very similar and many people think they are the same thing, but they are not.

### Why I decided to add analytics to my website?

While, I'm a small blogger and I'm probably not needing analytics, I decided to add them to my website. I only use analytics to make my website better(mostly I care about page time and visitors). As you can see, my intention is to make my website better, and I'm not using them for money.

### What I have been using?

Having analytics on a website in not a bad thing as long as you don't use Google Analytics. Google Analytics is a great tool, but it's not the only one and it used by Google and for tracking people for better advertising. After some searching, I found that I can use Plausible Analytics, which besides it is very privacy friendly (It collects very few data like screen size, location by country and browser), it's also a great tool for beginners, having only what you need. As a bonus, Plausible Analytics is FOSS software, so you can use it for free.

### How much data I collect from you?

The data I collect from you is very limited. For more information about what I collect, please read [Plausible Analytics's privacy policy](https://plausible.io/privacy-focused-web-analytics). If you are interested on what data I can see, please see [cristiioan.me public dashboard](https://plausible.cristiioan.me/cristiioan.me), on my own server.

### How I block ublock from blocking my analytics scripts?

Ublock is a great tool for blocking scripts(Including analytics scripts, tracking and ads) and I use it all the time. But since I do need some basic analytics data, I decided to proxy it to my main domain, basically I'm blocking ublock from finding my analytics scripts, making them look like they are needed for something else.
