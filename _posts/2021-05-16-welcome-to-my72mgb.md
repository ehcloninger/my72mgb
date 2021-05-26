---
title: "Welcome to My72MGB.com"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags: 
  - restoration
pinned: true
---

I've been working on a site for Pearline's adventures. I'm now ready to show it off. Warning, gory technical details ahead.

<!--more-->

[Bah! Screw all that, show me the pics!](https://www.smugmug.com/app/organize/My-1972-MGB)

When I started working on Pearline, I wanted to give her a separate site from my own personal blog. Not that I 
need that much separation between my personal life and this hobby, but I wanted to try out some new ideas with
a new website. This project gave me the opportunity.

My requirements for this site were to be easy to maintain without having to worry about hackers getting into my
site and making a mess of things. The easiest way to do this is with something called a "static site". This means
that there are no servers running software to operate the site itself. There are no databases, there are no 
'admin' users. In a way, it's back to the Internet of 1996, with much better graphics. From a technical standpoint,
it's way better than websites in 1996, because I can update it moderately easy.

Another big requirement is to be able to show off photos of my car while I rebuilt her. I also want to be able to
post photos of Pearline and I on our adventures. A lot of static sites have difficulty showing photos because that
task usually requires "back-end" servers to keep track of all the photos. The setup that I settled on handles 
photos very nicely if you have a certain form of OCD, which I happen to have. If I process my photos in a particular
way, they show up easily on these pages.

I have a social accounts on [Twitter](https://twitter.com/my1972mgb) and [Instagram](https://www.instagram.com/my72mgb/) 
that I plan to use to build a small following of old friends and new friends that we meet on the road.

### The Really Gory Details

If you're really interested in how all this works, the underlying technologies that run this site are:

* The [Jekyll](https://jekyllrb.com) publishing system, by GitHub
* Microsoft [Visual Studio Code](https://code.visualstudio.com/) for editing everything that I write and keeping all the files in their proper places
* The git version control system and the [GitHub](https://github.com) public repository hub
* The *Windows Subsystem for Linux*, for testing on my PC prior to making it public
* The [Netlify](https://netlify.com) build and deploy system. 

I recently switched to using Netlify after an online conversation with another Jekyll user. I was previously 
using Amazon AWS to host the site and handle all the plumbing that securely deploys and delivers the site. As 
an experiment, I tried a small site on Netlify and had it running within 15 minutes. That was all I needed to
switch. It took me about 30 minutes to get Netlify configured with DNS and LetsEncrypt.

With AWS, there's so much configuring because it's a general-purpose architecture. Netlify is made for my specific 
use case and others very similar to it. All the ugly parts are hidden behind a bunch of sane defaults. Oh, and it's 
free for personal use. Not that my $4/month bills on Amazon bothered me, but having a better system that costs 
nothing is pretty amazing.