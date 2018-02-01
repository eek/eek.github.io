---
title: How to serve your blog to a quarter million readers without paying a single
  penny
date: 2016-08-21 10:56:00 Z
categories:
- technology
- hosting
- cloudflare
- jekyll
- github
layout: post
description: A blog that can stand to any number of visitors without paying a single
  penny, this is why we all love the internet today. Say hello to Github Page, Cloudflare
  and Jekyll
ogimage: "/assets/img/github-pages-cloudflare-jeyll-love.jpg"
imgwidth: 1200
imgheight: 630
---

It’s been a while since my first blog post (10 months) – [Why BPG will replace GIFs and not only]({% post_url 2015-10-20-why-bpg-will-replace-gifs-and-not-only %}) - which gathered a lot of attentions (~ 250k users that shared it 41.5k shares)

… the cool part is that I haven’t paid anything in hosting costs

I always wondered…

>Why in a world in which processing power is so cheap, so many blogs load so slow and cost so much to keep them running?

If you wanna know why, stay tuned for the upcoming blog post, in a day or two! [Sign up to my newsletter](#mc_embed_signup) and I'll let you know.

My dilemma was simple:

>Is there a way anyone can host a blog on his own domain with SSL (HTTPS) enabled that can handle millions of users without paying a single penny?

The response is surprisingly simple:

>YES.

#### And you only need to know 3 things:

1.	**GitHub Pages.**
  *  [GitHub Pages](https://pages.github.com/) is the holy grail of hosting. They give you free hosting for your vanilla website or Jekyll blog.

2.	**CloudFlare**
  *  [CloudFlare](https://www.cloudflare.com/) is the de facto standard of modern website caching, security and DNS services. If you don’t already have a Cloudflare account… I feel sorry for you. It’s like missing free chocolate🍫🙀

         *You need a CloudFlare for:*
    *	**DNS**: To point your domain to Github Pages
    *	**HTTPS**: They add SSL to your websites without a fuss so your visitors can feel secure
    *	**Extra Caching**: They can cache and serve everything to make your blog really really fast.
    
3.	**Jekyll**
  *  It’s a static site (blog) generator. [More about Jekyll here](https://jekyllrb.com/)
  *  You can find [Jekyll themes for your blog here](http://jekyllthemes.org/)

With Jekyll you write each post as text (Markdown actually – [there’s a good cheat sheet made by Adam Pritchard on GitHub](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)) and it compiles to a full website (HTML), no need for a database so it’s like having your WordPress blog always cached.

#### Disadvantages?

I thought you guys would never ask…

Yup, there are **a few**.

1.	**Your website will be public on GitHub**, so anything secret you add to those files will be accessible to anyone
  *	But who adds secret things to Front-End files anyway?
2.	**People can copy your website**
  *	But if you used a free theme it doesn’t matter anyway, lol
3.	**You don’t have an admin panel**
  *	Not having something like the [WordPress](https://www.wordpress.org) admin might be painful for beginners and also dealing with Markdown might annoy you at first (unless you don’t already use StackOverflow, GitHub or Slack and know a bunch of Markdown already)
4.	**You don’t have a database, so you can’t really store anything**
  * But there are a ton of 3rd party tools that can help you with whatever you want, things like:
  *  [Google Analytics](https://analytics.google.com) for Analytics.
  *  [Hotjar](https://www.hotjar.com/) for User Recordings, Heatmaps, Funnels, Forms, Polls and Surveys.
  *  [Shareaholic](https://shareaholic.com/) for Acquiring, Engaging, Analyzing and Monetizing content.
  *  [GetSiteControl](https://getsitecontrol.com/) for Surveys and Email opt-ins, Contact forms and Popups, Follow and Share buttons and Live chat.
  *  [Sumome](https://sumome.com) for List Builder, Heat Maps, Sharing Widgets, Scroll Boxes, Highlighters, Contact Forms, Image Sharing, Welcome Widgets, Content Recommendations, etc…
  *  [Disqus](https://disqus.com) for commenting (or [Facebook comments](https://developers.facebook.com/docs/plugins/comments/) if you like those more)
5.	You will need to know a bit of **Git** ([there’s a good guide by Roger Dudler here](http://rogerdudler.github.io/git-guide/) to be able to push your updates to the blog.
  *	But don’t freak out, that’s super simple, you just need to follow the instructions to set it up and then after you finish with something just write `git push` in the terminal

If you're into techie stuff, these disadvantages might be just something fun to do! Especially since you can get everything for free! :D


PS: If you want to get started right away, CloudFlare even posted a step-by-step tutorial for you to get up and running in no time! :D Check it out: [https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/](https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/)

PPS: I feed off shares, so if you like this article, share it! :D