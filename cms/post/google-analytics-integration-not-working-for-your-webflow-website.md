---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I recently had a client email me because they were having trouble integrating
  Google Analytics with their new Webflow website I built for them.Webflow has a
  native Google Analytics integration where you can just enter your Google
  Analytics Tracking ID and click 'Save Changes' and 'Publish':
title: Is the Google Analytics Integration Not Working for Your Webflow Website?
slug: google-analytics-integration-not-working-for-your-webflow-website
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/webflow.md
  - cms/tag/website-analytics.md
updated-on: '2023-04-26T19:00:44.869Z'
created-on: '2023-04-26T19:00:44.869Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

I recently had a client email me because they were having trouble integrating Google Analytics with their new [Webflow](https://webflow.grsm.io/4623107) website I built for them.

[Webflow](https://webflow.grsm.io/4623107) has a native Google Analytics integration where you can just enter your Google Analytics Tracking ID and click 'Save Changes' and 'Publish':

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64497439e9e76bb58148963f_220c4520-f8f7-4c91-beae-29ee6183c643.jpeg)

Seems easy enough right?

Well, here's where the confusion lies and the problem my client was having; this integration is only for Universal Analytics, which is a specific version of Google Analytics. You can tell by looking at the tracking ID. It starts with "UA".

What's wrong with that?

Well if you go create a new Google Analytics account for a new website today, you don't get Universal Analytics. You get Google Analytics 4 by default, which is their latest iteration of Google Analytics and it has a different type of tracking ID.

You'll recognize a Google Analytics 4 tracking ID because it starts with "G" instead of "UA".

To install Google Analytics 4 into [Webflow](https://webflow.grsm.io/4623107), you'll simply copy the script and paste it in the Custom Code section of your Webflow site.

You can find the Google Analytics 4 script in the admin area. Click on the gear icon in the bottom left corner of the screen and then click on 'Data Streams':

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64497439821df796b1a08155_CleanShot-2021-03-24-at-19.29.55%402x.jpeg)

Click on the Data Stream for your website:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644974393f0674c9d5629e12_CleanShot-2021-03-24-at-19.32.51%402x.jpeg)

Next click on the dropdown arrow to reveal the script:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64497439e05557739b47e940_CleanShot-2021-03-24-at-19.34.19%402x.jpeg)

Then you'll find the script for installing on your Webflow website. Go ahead and copy that to your clipboard:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/6449743a9d76bf568deac521_CleanShot-2021-03-24-at-19.35.09%402x.png)

Then paste:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/6449743a5fe6d139699d88b3_CleanShot-2021-03-24-at-19.41.40%402x.jpeg)

Hit 'Save Changes' and 'Publish' and you're good to go!

‍
