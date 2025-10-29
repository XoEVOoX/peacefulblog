---
title: Search Like a Pro
date: 2025-10-29T01:07:00
draft: false
featured: false
pinned: false
images:
description: Learn how to Google like a pro...by avoiding Google entirely!
categories: Privacy
series:
tags:
  - Browser
  - Search
  - De-Google
comments: true
---
### **>** You're doing too much. 🙅‍♂️
If you're anything like me, you've probably spent the majority of your life searching your favorite content hub via Google queries.  I'm here to help cleanse you of that habit. It's simpler than you might think! Let's get into it!

### **>** Any database is a search engine if you're brave enough. 🫵
In most modern browsers, in the settings page, when you navigate to "Search" and scroll down, you will see a section labeled "Search Shortcuts". This is your key to freedom from Google knowing everything you look for online. Let's take a look at my GitHub search shortcut.

![Testing](Screenshot%20from%202025-10-29%2001-18-56.png)

It's pretty self explanatory. After you select the <kbd><kbd>Add</kbd></kbd> option you will see an empty prompt with the following options. This will hold true to both Chrome, and Firefox. I'm sure most browsers will have similar features but I don't have time to test it right now. 

#### Search engine name
It is what it sounds like. This will be the title of your search shortcut in your search menu. The name here won't affect functionality. Name it something descriptive, or whatever the hell you want. 

#### URL with %s
This is the meat and potatoes of the whole feature. `%s` denotes a string, which is a just a sequence of characters. Now that you know what it means, you're gonna start to see it everywhere as you browse the web. Navigate to your favorite content hub and search for anything. I'm going to pull an example query from wikipedia. This is what a search looks like in the toolbar:
`https://en.wikipedia.org/w/index.php?search=2025+Louvre+Robbery`

Where do you think the string begins here? 

`https://en.wikipedia.org/w/index.php?search=`<mark>2025+Louvre+Robbery</mark>

So to create a proper search shortcut we would take this url and modify it like so:

`https://en.wikipedia.org/w/index.php?search=%s`

Now when we use this shortcut, it will populate the query to include your string automagically! 

#### Keyword
This section is optional but I highly advise it for the sake of the workflow. You type this shortcode into your browser and it will initialize the search engine for the site that you configured it for automatically. When I type `git` into my browser, my GitHub search engine is initialized and ready to search GitHub. It's a revelation! 

### **>** Happy Google-Free Searching!
This may not solve *all* of your Google related woes. Some sites may not have a robust enough search feature. (Looking at you, Reddit.) In that case, for now, I suggest searching via a search engine that is committed to privacy, such as DuckDuckGo, Brave, or Startpage. Once you get a few of these shortcuts configured, you're going to be amazed at the time you save, skipping over the gatekeeper that is Google. 