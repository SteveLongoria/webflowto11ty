---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I have a friend that's been setting up his new ecommerce shop using Webflow
  recently and I was helping him set up sales conversion tracking for the
  shop.He'd never used Google Analytics so when he went to create a new one, of
  course, it created a new Google Analytics 4 account.Initially, this seems like
  an issue because when you go to your Webflow project settings, you'll see
  there's only a place to insert your Universal Analytics Tracking Code:
title: Webflow Ecommerce Sales Conversion Tracking with Google Analytics 4 (GA4)
slug: webflow-ecommerce-sales-converion-tracking-with-google-analytics-4
f_tags:
  - cms/tag/webflow.md
  - cms/tag/conversion-tracking.md
  - cms/tag/google-analytics.md
  - cms/tag/ecommerce.md
updated-on: '2023-04-30T22:12:44.729Z'
created-on: '2023-04-30T22:12:44.729Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

I have a friend that's been setting up his new ecommerce shop using [Webflow](https://webflow.grsm.io/4623107?ref=freak.marketing) recently and I was helping him set up sales conversion tracking for the shop.

He'd never used Google Analytics so when he went to create a new one, of course, it created a new Google Analytics 4 account.

Initially, this seems like an issue because when you go to your [Webflow](https://webflow.grsm.io/4623107?ref=freak.marketing) project settings, you'll see there's only a place to insert your Universal Analytics Tracking Code:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644ee7a4148b86137b0b5069_CleanShot-2022-08-08-at-10.36.00%402x.png)

Sure you can insert it in the 'Custom Code' section but to use e-commerce event tracking, you need to integrate in the Integrations tab and toggle on the option for the global site tag.

This has you assuming that GA4 e-commerce conversion tracking isn't yet an option for Webflow, but then when you go to [their documentation on setting up Google Analytics](https://university.webflow.com/lesson/set-up-google-analytics?ref=freak.marketing), you'll notice they're adding a GA4 measurement ID:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644ee7a3217bee05196bdeee_image.png)

To be on the safe side I'd probably still use Universal Analytics but it appears you can also use GA4 now too.
