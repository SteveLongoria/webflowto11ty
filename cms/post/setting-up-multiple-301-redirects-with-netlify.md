---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I've been hosting my Hexo blog with Netlify for the past 2 years. I have no
  major complaints with Netlify hosting, but recently I've decided to move my
  personal blog over to Webflow. I already have my main website built using
  Webflow so I just wanted to 'bring all under one roof' so to speak.I of course
  didn't want to lose my rankings I've acquired in the Google SERPs over the
  past 2 years. 
title: Setting up Multiple 301 Redirects With Netlify
slug: setting-up-multiple-301-redirects-with-netlify
f_tags:
  - cms/tag/web-development.md
  - cms/tag/seo.md
updated-on: '2023-04-22T19:55:19.375Z'
created-on: '2023-04-22T19:55:19.375Z'
published-on: '2023-04-26T03:04:24.119Z'
layout: '[post].html'
tags: post
---

I've been hosting my Hexo blog with Netlify for the past 2 years. I have no major complaints with Netlify hosting, but recently I've decided to move my personal blog over to Webflow. I already have my main website built using Webflow so I just wanted to 'bring all under one roof' so to speak.I of course didn't want to lose my rankings I've acquired in the Google SERPs over the past 2 years.

This means setting up 301 redirects.Netlify has 2 ways to do this. You can use a file named \_redirects.txt, placed in the 'publish directory' for the project. The other was by creating a file called netlify.toml and placing it in the root directory for the project.I first tried the \_redirects.txt file without any luck. I must admit I'm not too knowledgeable of Hexo or static site generators in general. It had been 2 years since I had originally set up this blog and since then have done less coding and have been using git and terminal a lot less.

I then tried netlify.toml. This ended up being a lot simpler and worked right away. The documentation didn't really specify what to do if you had multiple URLs that you want to set up 301 redirects for in a single file but after some quick troubleshooting, I figured out that you need to repeat the \[\[redirects\]\] heading for each 301 redirect.You can [view my netlify.toml file on Github](https://github.com/SteveLongoria/hexo-blog/blob/master/netlify.toml?ref=freak.marketing) to see how it should be formatted for multiple redirects.
