---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  When setting up conversion tracking for a new PPC ad campaign, whether it's
  Google Ads, Facebook Ads or whatever, it's important to track every possible
  way a website visitor can become a lead or customer.For most websites, this
  typically means tracking calls and contact form submissions. But what about
  that random email address on the contact page or footer?Is it possible to
  track when website visitors send an email from your website as a conversion?
title: Tracking Conversions When Someone Sends an Email Directly From Your Website
slug: track-website-email-link-conversions
f_tags:
  - cms/tag/conversion-tracking.md
  - cms/tag/google-tag-manager.md
updated-on: '2023-04-30T18:09:48.469Z'
created-on: '2023-04-30T18:09:48.469Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

When setting up conversion tracking for a new PPC ad campaign, whether it's Google Ads, Facebook Ads or whatever, it's important to track every possible way a website visitor can become a lead or customer.

For most websites, this typically means tracking calls and contact form submissions. But what about that random email address on the contact page or footer?

Is it possible to track when website visitors send an email from your website as a conversion?

Kind of but it's not perfect! If you have your email address hyperlinked, meaning visitors can tap or click on the email address to automatically open their email client to compose an email to that email address, you can track clicks on the email hyperlink as a conversion.

Obviously, this doesn't tell you if they actually sent the email or not. Also, you're not able to track when visitors simply copy and paste the email address into their email client.

Tracking clicks on the email address hyperlink is the best option.

Typically, I recommend just removing the email address and sticking with the contact form and phone calls or even just a chat.

If that's not an option for whatever reason, it's easy to setup conversion tracking for when visitors click on the email address hyperlink using Google Tag Manager.

Simply set up a trigger for when somebody clicks on a link that contains "mailto" in it. Then create a tag using that trigger.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eaec50c513949f9d70e71_CleanShot-2022-06-05-at-11.26.53%402x.png)

Then set up whatever tags you need with that trigger; like Google Ads or Google Analytics.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eaec5c1fef0655dfa93c8_CleanShot-2022-06-05-at-11.29.45%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eaec57fa5446a97156de2_CleanShot-2022-06-05-at-11.31.07%402x.jpeg)

Don't forget to set up the Google Analytics Goal to listen for the event category and action you inserted in Google Tag Manager.
