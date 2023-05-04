---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  You have a sweet new Carrd.co landing page and you're wanting to advertise it
  via Google Ads. There's just one problem.You're not sure how to set up Google
  Ad Conversion tracking for the Carrd.co form because it doesn't redirect to a
  unique thank you page URL. And this is because all Carrd sites are technically
  only one page. Carrd simply creates the effect of having a multi-page website
  by using HTML anchor links.
title: Track Carrd.co Form Submissions as a Google Ad Conversion
slug: track-carrd-form-submissions-as-google-ad-conversion
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/conversions.md
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
updated-on: '2023-04-30T20:36:49.968Z'
created-on: '2023-04-30T20:36:49.968Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

You have a sweet new Carrd.co landing page and you're wanting to advertise it via Google Ads. There's just one problem.

You're not sure how to set up Google Ad Conversion tracking for the Carrd.co form because it doesn't redirect to a unique thank you page URL. And this is because all Carrd sites are technically only one page. Carrd simply creates the effect of having a multi-page website by using [HTML anchor links](https://coder-coder.com/make-html-anchor-link-jump-specific-part-of-page/?ref=freak.marketing).

So how do you track form submissions? Well, since the Carrd form submission also doesn't trigger the default 'form submission' trigger in Google Tag Manager, I've had to set up a trigger based on when the website visitor clicks a button with the 'Click Text' of 'Submit' or whatever your form submission button text says.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644ed138946b855a7473d928_CleanShot-2022-07-01-at-11.31.56%402x.jpeg)

Don't forget to make sure you have the 'Click Text' variable enabled here as well:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644ed1382977e1c4989d105a_CleanShot-2022-07-01-at-11.32.32%402x.jpeg)

‍
