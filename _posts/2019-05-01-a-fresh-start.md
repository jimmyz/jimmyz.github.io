---
layout: post
title: A Fresh Start
date: 2019-05-01 03:34 -0600
---
I have decided to take a fresh start with my website. I've been exploring all sorts of different options for website design, website creation, and website hosting. My main requirements for this included:

1. *Low cost*. This needs to be inexpensive as this is a personal website, not a commercial endeavor.
2. *Keep my own domain name*. I've had this jimmyzimmerman.com domain for a long time and I'd like to keep using it.
3. *TLS support*. I want this in order to keep vulnerabilities as low as possible, and [for search rankings](https://webmasters.googleblog.com/2014/08/https-as-ranking-signal.html).
4. *Markdown support*. I've come to really enjoy the simplicity of markdown to control the formatting of a document.
5. *Easy to maintain*. I don't have a ton of time to fidget with a website. I don't want to manage and patch my own web servers and software. The easier to maintain, the better.
6. *Provides a learning experience*. I enjoy things most when I'm learning something new along the way.

The solution I landed on is to is to use Github Pages with Jekyll. This meets all of my requirements.

||Requirement|Evaluation|
|----|----|----|
|✅|Low cost|Github pages is free. I only pay for a domain name, which is cheap.|
|✅|Keep my own domain name|[Github supports this](https://help.github.com/en/articles/using-a-custom-domain-with-github-pages).|
|✅|TLS Support| Uses [Let's Encrypt](https://letsencrypt.org/), which provides free SSL/TLS certificates. Github sets this up and manages it for me.|
|✅|Markdown Support|Jekyll supports markdown natively. I just create markdown files and it does all of the conversion for me automatically. When I check in my changes to Github, it publishes it with this nice theme.|
|✅|Easy to maintain|Ultimately, everything from this website gets compiled to static HTML, JS, CSS, and image files. I let Github manage all of the server maintenance. Easy peasy!|
|✅|Learning experience|Overall, this has been a good learning experience for me. I've enjoyed learning how to build a website using Jekyll. I've had fun exploring various theme options and Jekyll plugins.|

Now the real test will be to see if this helps me to actually start writing again. My old blog had gone dark as my last post was made several years ago. I archived its content as a Wordpress.com blog. I didn't bother with redirects because the content shouldn't be very valuable to anyone.