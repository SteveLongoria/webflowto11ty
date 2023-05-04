---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I had recently written a blog post on how to set up Google Ad Conversion
  Tracking for website forms that don't redirect users to a 'thank you' page
  after submission.This works great if the site just has one form like a
  'contact form', and in some situations it works for websites that have
  multiple forms but sometimes you want to set up different conversion tracking
  for each unique form on your site.The easiest way to do this is to set a
  unique ID on each form, so that you can set up a Google Tag Manager Trigger
  for each form using the unique ID, and then a unique Tag for each Trigger you
  make here:
title: >-
  Conversion Tracking for Multiple Different Forms on a Website without 'Thank
  You' Pages
slug: conversion-tracking-for-multiple-forms-without-thank-you-pages
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/google-tag-manager.md
  - cms/tag/conversion-tracking.md
  - cms/tag/conversions.md
updated-on: '2023-04-29T05:24:57.108Z'
created-on: '2023-04-29T05:24:57.108Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

I had recently written a blog post on [how to set up Google Ad Conversion Tracking for website forms that don't redirect users to a 'thank you' page](https://freak.marketing/track-form-submissions-as-conversions-without-thank-you-page/) after submission.

This works great if the site just has one form like a 'contact form', and in some situations it works for websites that have multiple forms but sometimes you want to set up different conversion tracking for each unique form on your site.

The easiest way to do this is to set a unique ID on each form, so that you can set up a Google Tag Manager Trigger for each form using the unique ID, and then a unique Tag for each Trigger you make here:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644ca9f607dc212f25326b1d_CleanShot-2022-04-16-at-11.23.41%402x.png)

But sometimes it's not so easy to add ID's to each form because you're not the dev or the dev is difficult to reach.

In these cases, you will have to set up a General Form submission trigger first and click the Google Tag Manager Preview Button so we can manually submit the forms and look for unique attributes in the Click or Form Classes in Tag Assistant mode.

I also commonly set up Form Submission triggers based on which page URL the form is on. That's also another common way to differentiate between the forms when they don't have unique IDs or Classes.

‍
