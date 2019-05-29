---
layout: single
title: IPFS Learnings So Far
excerpt: It has been about one week of hands-on experience with IPFS. Here's my experience
  so far.
category: Technology
tags: ipfs distributed-web
image-from: https://pixabay.com/...
header:
  overlay_image: "/assets/images/posts/IPFS_logo.png"
  overlay_filter: 0.5
  caption: 
  og_image: "/assets/images/posts/IPFS_logo.png"
date: 2019-05-29 08:06 -0600
---
It has been about one week of hands-on experience with IPFS. I'm doing this in 30 minute intervals so my learning isn't progressing super quick. Here's what I've learned so far.

Installing IPFS was relatively easy, though I was hoping that it would have had a `brew` package for installing on a Mac. Sounds like [there are plans for this in the future](https://github.com/ipfs/distributions/issues/22), perhaps when it stabilizes a bit more and hits v1.0. I found it interesting that the recommended IPFS implementation for install is written in Go.

IPFS has pretty nice [getting started documentation](https://docs.ipfs.io/introduction/usage/). However, I ran into issues right off the bat because my laptop was connected to a network with very tight restrictions. It appeared that everything launched successfully. I was given no errors in the terminal, things just didn't work. I then tried connecting to a more open hotspot and was able to get a bit further, but I still couldn't complete the first getting started tasks successfully.

My next attempt was to fire up a micro server in EC2, install and try things out there. This worked much better. I was able to find peers and was able to serve up a file which was found on the gateway. I'm making progress, but I still have a ton to learn. I'm just scratching the surface.

I believe protocols like IPFS will gain traction and will become a core part of our future Internet experience. The following video makes some very compelling arguments.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/skMTdSEaCtA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>