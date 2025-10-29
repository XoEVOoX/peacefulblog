---
title: Start Watching Youtube Locally
date: 2025-10-21T06:30:00
draft: false
featured: false
pinned: false
images:
description: It's time to be more deliberate in our online media consumption.
categories: Privacy
series:
tags:
  - YouTube
  - De-Google
comments: true
---
[Enshittification](https://en.wikipedia.org/wiki/Enshittification) is running rampant on YouTube. It seems like every week, the site's quality declines, or Google issues new veiled threats against users of ad blockers like uBlock Origin. It's time to take back the reins in this relationship. It's time to start watching YouTube locally.

### What does watching something 'locally' even mean?

Consuming content 'locally' means accessing it directly from your physical device's storage. When you take a picture on your phone and view it in your gallery, you are consuming that content locally. No one who doesn't control your device knows you viewed it, and no one can take it away from you, limit its quality, or charge you to store or view it.

This changes once you send that picture to a service like Amazon AWS, Google Cloud, or Apple iCloud—especially if you don't keep local copies. You've now delegated your ability to view that picture to a company that can choose to do any of the above, or even unilaterally *delete it* altogether. I'm sure I don't have to explain why that is... less than ideal.

### How do you start watching YouTube locally?

There are many tools and methods for downloading local copies of YouTube videos. This isn't a detailed guide, but I will share a couple of well-established tools for obtaining video files so you can serve them locally.

#### [YT-DLP](https://github.com/yt-dlp/yt-dlp)

The gold standard and the workhorse behind most GUI YouTube downloaders. This is often considered an option for advanced users, but with the help of LLMs like ChatGPT, anyone can set up an efficient workflow. It has powerful potential for automation; with a little tinkering, you can do amazing things. 

A quick note for Debian users: the version in `apt` is often out-of-date. It's best to grab the Python 3 version.
{: .box-warning}

#### [Stacher](https://stacher.io/)

For everyone else, or for those who prefer a graphical interface over building a workflow from scratch, I recommend Stacher. The interface is clean, it's simple to set up, and you can manage everything from the application window. You won't have the granular control of a custom YT-DLP setup, but it significantly simplifies the process.

![Stacher Website](https://stacher.io/static/media/5.757a5816db828a34e053.png)

### Is this legal?

Yes, it is legal. When you watch a video on a website, your browser downloads and caches it to serve it to you. You are already downloading the video when you watch it. Tools like these simply let you download the video to watch *later*. YouTube doesn't know when you watched it, how long you watched it, or if you skipped around. All they know is that someone from your IP address (if you even allow that!) requested the content. You won't be served ads, and Google doesn't get to learn more about you to convert into ad revenue.

### The Downside

There is a downside. By circumventing the ads, you also deprive your favorite content creators of ad revenue. Thankfully, there are many other ways to support them, such as Patreon, PayPal donations, or purchasing merchandise directly.

### Wrapping Up

It's time to take back control of our media consumption. Big corporations made it easy to outsource our access, and in doing so, they've fenced off the watering hole. They've shoehorned us into subscription models, hiked the prices, and watched us squirm. We shouldn't sit idly by as we are treated as commodities by corporations that don't care about us, all while our user experience becomes measurably worse.

Do what you can to fight enshittification, but also remember to support your favorite creators. They've committed to the idea that they can 'make it' on these platforms, and we don't want to see them suffer.

Thanks for coming to my TED Talk.
