---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  There are a lot of situations where you may have your website visitors bounce
  around across your root domain (yourdomain.com) and sub-domains
  (subdomain.yourdomain.com).I recently had this situation arise for myself. I
  have my Ghost blog hosted on the root domain (freak.marketing) and since I
  can't easily edit this theme to add a proper direct response optin page for my
  new online course, I used Carrd.co (aff link) to create it. I then pointed the
  landing page at a sub-domain (stripe.freak.marketing).Simply adding the Google
  Analytics script to this sub-domain isn't going to give me accurate conversion
  data. For example, let's say a visitor comes in to Freak.Marketing via organic
  search. They then click over to stripe.freak.marketing where the Carrd lead
  magnet page is pointing and optin there.
title: >-
  Set Up Google Analytics Cross-Domain Conversion Tracking with Google Tag
  Manager (GTM)
slug: google-analytics-cross-domain-conversion-tracking-with-gtm
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/conversion-tracking.md
  - cms/tag/conversions.md
  - cms/tag/google-tag-manager.md
updated-on: '2023-04-30T18:17:39.144Z'
created-on: '2023-04-30T18:17:39.144Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

There are a lot of situations where you may have your website visitors bounce around across your root domain (yourdomain.com) and sub-domains (subdomain.yourdomain.com).

I recently had this situation arise for myself. I have my Ghost blog hosted on the root domain (freak.marketing) and since I can't easily edit this theme to add a proper direct response optin page for my new online course, I used Carrd.co ([aff link](https://try.carrd.co/4ldc14z2?ref=freak.marketing)) to create it. I then pointed the landing page at a sub-domain (stripe.freak.marketing).

Simply adding the Google Analytics script to this sub-domain isn't going to give me accurate conversion data. For example, let's say a visitor comes in to Freak.Marketing via organic search. They then click over to stripe.freak.marketing where the Carrd lead magnet page is pointing and optin there.

The basic set up of Google Analytics would attribute this conversion to freak.marketing, not organic search like it sould be attributed.

To fix this, it's as simple as making a small edit in Google Tag Manager (GTM). This is assuming you have Google Analytics set up via a GTM tag.

You edit the custom Google Analytics Variable you're using with your Google Analytics Tag:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eb09b7e5870624794c0bd_CleanShot-2022-06-19-at-11.32.30%402x.jpeg)

Google provides instructions for [this here in their documentation](https://support.google.com/tagmanager/answer/6164469?hl=en&ref=freak.marketing).
