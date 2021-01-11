---
layout: single
title: Fun with Raspberry Pi
excerpt: 
tags: technology linux raspberry-pi
category: Life
date: 2021-01-11 12:46 -0700
---
In this post, I'm going to share what led me to diving into Raspberry Pi and what I've discovered so far.

A week ago, our 27" iMac began having problems. I've narrowed down through various troubleshooting techniques that there must be some sort of hardware problem. So, it is time to buy a new computer. The order is in, but Apple is backordered on almost ever Mac computer and it will take several weeks until we get the new one.

This beloved iMac was our family computer that sat in our main room on a fairly small desk. Our kids used this computer _a lot_. They would stream their favorite shows through [Disney+](https://www.disneyplus.com/), [PBSKids](https://pbskids.org/), and [BYUtv](https://www.byutv.org/). They also played a lot of Roblox and Minecraft. My wife also used it to write our family blog and to house our 1.2 TB library of family photos and videos. How are we going to survive for so long without this family computer?

As I contemplated this question, I remembered that I had purchased a couple of Raspberry Pi's a couple of years ago. There was a flash sale that seemed too good to pass up and I believe I got 2 Raspberry Pi 3+ machines, including cases for about $100.

My ambition in purchasing these Pi devices was to setup RetroPi, and buy some other devices from eBay to rip some of my old Atari games into ROMs to play with my kids (keeping everything legal). It sounded like a total hacker type project that would great fun. But, I discovered that my old Atari and a large collection of the games was secretly donated to the local thrift store years before. Ouch! But, in all fairness, it hadn't been touched for years. #forgiveness

Back then, I played around with the Pi for a bit, but abandoned it because I didn't want to get into downloading ROMs where the legality is in question. I lost interest and the Raspberry Pi's sat in my closet for a while.

So, here comes the Raspberry Pi to the rescue. I ended up installing the basic Raspberry Pi OS to the Micro SD card and firing it up. I like the Pi OS as it is a really basic Debian-based OS. It felt familiar enough to me.

The first thing I did was try to test out Disney+ and its ability to stream. I ran into problems. [I followed this guide](https://www.tomshardware.com/how-to/play-netflix-raspberry-pi) to patch Chrome in a way that at least enables some streaming. Disney+ still doesn't work. But, Youtube, PBSKids, and BYUtv almost work okay. The video will briefly pause where memory or processing hits a bottleneck. I've heard overclocking the Pi can help surpass that, but I haven't tried that yet.

The streaming experience so far has been poor enough that my kids will only use the Pi to stream if it is the last resort.

Oddly, the thing that has caught the most wonder and attention of my kids is the screensaver. What!? Seriously, they love the screensavers. I had to install XScreensaver and several packages to get the full collection loaded on the Pi. There are about 100 different screensavers, and they love exploring, changing the options, and showing them off to each other. My son laughed at the [Bouncing Cows](https://www.youtube.com/watch?v=O_b5UWhv49w) screen saver and the flying toasters. This seems like such old school stuff, but they really like it!

The other thing that has captured their attention is the Games available. I installed about 50 games. I couldn't remember what I set the `pi` user's password to, so for some reason I can't use the GUI app installer, but installing via the Terminal works. So, I taught my eight year old son how to use apt-get to install games based upon the package name. Seeing him do that was a proud parent moment, though he did say to me, "Dad, this is like really old computer stuff, right?" Well, not so old.

A couple of games have been winners. The top game would be [Pingus](https://pingus.seul.org/) which a lot like Lemmings. My kids have never played Lemmings, so this was a brand new experience for them. The next favorite game would be Minecraft PI Edition.

We've only tried about a dozen of the games so far, but the Pi has provided some level of entertainment for the kids.

I still can't wait for the new iMac to come, but I admit I probably spent way to much money on it. I'm surprised that the last one died as soon as it did, but I guess 6 years seems about right for a computer. Although I still have a MacBook Air from 2011 that is doing fine.

That's all for today.
