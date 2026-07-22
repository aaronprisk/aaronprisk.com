---
layout: post
title: "Now comes good sailing"
date: 2026-07-22
description: "Introduction to Walden - A minimal, distraction-free, local desktop blog publisher"
tags: [Linux, Ubuntu, Snap, Walden]
---

To kick off this summer, I decided to read the novel Walden by Henry David Thoreau, the great American novelist and transcendentalist thinker. Almost immediately did I feel a strong kinship to Henry and his desire to escape the often overwhelming and obfuscating nature of modern life. To capture, as he puts it so eloquently, “..to want but little.” This yearning to find joy, peace and contentment in having less when there is a constant barrage of voices pushing you to pursue more.

## My slice of the interwebs
Around the same time, I realized that my personal website (the one you are visiting at the moment) was a bit dusty. It had gone through two major revamps since I first registered the domain back in the early twenty teens. Its first incarnation was a Wordpress backed blog where I would share my work deploying Linux in schools and other nerdy side projects. It was from that site that I was discovered by an editor from OpenSource.com (Looking at you Don!) and encouraged to pen a couple articles for their site. That was an amazing experience and I was shocked at how far my few articles traveled and the sheer volume of people who read them. I still have folks reach out to me on LinkedIn telling me how one of my articles helped them do something cool. 

So with the lack of need for a personal blog plus the added headache of keeping my Wordpress up to date and secured from the non stop bot attacks, I decided to shift to a static website. I opted for a simple bootstrap driven site that acted a bit more like a resume or museum of work where I would include links to some of my favorite articles and projects and that's mostly how it remained for a decade. A few theme changes and little easter eggs here and there, but very much a site largely frozen in time. 


## The blog is dead. Long live the blog.
2023 rolls around and Red Hat pulls the plug on OpenSource.com along with my preferred space to share the fun, geeky stuff I was tinkering with. With it gone and my focus mainly shifting to new job opportunities and family life, I shelved my personal publishing hobby.

Back to the current times, while I was scoping out the rebuild for my website, I decided that I missed having that little space where I could jot down some thoughts in a less rigid or structured manner. I decided I was going to spin up a new blog and it was NOT going to be Wordpress this go around. I also decided to move away from my trusted VPS instance on Digital Ocean that had basically been running like a champ for nearly 10 years. Pour one out for a legend.. 


## Less is more
Naturally I checked out the various static site generators out there like Jekyll, Hugo, Gatsby along with the various tools used to publish to them. They're all stellar pieces of software and all have a lot to offer, but.. I wanted something so simple, so barebones, and so zen that it feels like it could belong on my old Commodore VIC-20. As any Linux nerd does, I couldn't find exactly what I wanted so I opted to build something else!

* The questions that naturally arise are probably:
* Aren't there other static site publishing tools out there? Yep.
* Do those tools have more bells and whistles? Most certainly. 
* Do we really need yet another piece of software out there to do X? Nah.. probably not.
* So why go to all the trouble? Because it's fun! :)

## By Walden pond
After a weekend of coffee fueled late nights, Walden was born. 

![Image Description](/img/asset-1784747310429.png)

It features the following:
* Sleek and simple markdown editor powered by EasyMDE
* Ability to sync with a GitHub pages (Jekyll) or a plain old /blog directory
* Essential SEO settings for discoverability
* Easy image uploading and linking
* Local draft saving 
* ..and that's about it.

These markdown files are pushed to my website repo, Github pages does it's Jekyll-y background magic and the next time someone visits my site, they will be greeted to a nicely rendered collection of thoughts. That's it! Nothing too sexy, but exactly what I was hoping for. I know that I can simply install Walden on any device, toss in my settings and start jotting down my thoughts. Aside from some basic quality of life improvements and bug fixes, I don't plan on adding much more to it. After all - *"A man is rich in proportion to the number of things he can afford to let alone"*

## In a Snap
I'm sure I will be accused of bias here due to my affiliation with Canonical, but I genuinely appreciate the simplicity of Snaps. With Walden being a very simple Electron app with a small number of libraries, I was able to package it up and get it onto the Snap store in no time. In the future when I need to push updates or bugfixes, it's extremely trivial and can be done in a matter of minutes. 

Now I have no idea if my unique brand of silliness and love for a purposefully limited blogging app will be of value to others, but I hope it does. Even if it's only one other human out there who sees the value in it, then I am happy! If that's you, give it a go:

[![Snap](https://snapcraft.io/en/dark/install.svg)](https://snapcraft.io/walden)

Or simply run:

**snap install walden**

## Raise your sail

As you can probably imagine, this post was written and posted via Walden. Now that it's out the cabin door, I can focus on more "Technical writings, Open Source projects and other nerdy musings." Cheers!

*Also, please go read Walden.. It's a beautiful book and so desperately needed right now. *
