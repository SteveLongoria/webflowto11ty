---
f_featured: false
f_color: hsla(0, 0.00%, 0.00%, 1.00)
title: Thank You Page Conversion Tracking In Google Analytics 4 (GA4)
f_post-summary: >-
  You have a new marketing website all set up to generate leads for your
  business but there's just one problem; before you can start advertising your
  website, you need to set up "thank you page" conversion tracking in Google
  Analytics 4 so you can know which marketing channels are driving the most form
  submissions (i.e. leads).In GA4, it's actually not possible or necessary to
  set up form submission conversion tracking to fire on the "thank you" page.
  GA4 has what's called "Enhanced event measurements" which will automatically
  fire 2 events for your HTML form:
slug: thank-you-page-conversion-tracking-in-google-analytics-4-ga4
updated-on: '2023-04-22T03:06:00.195Z'
created-on: '2023-04-18T19:44:08.278Z'
published-on: '2023-04-22T12:56:55.384Z'
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
layout: '[post].html'
tags: post
---

You have a new marketing website all set up to generate leads for your business but there's just one problem; before you can start advertising your website, you need to set up "thank you page" conversion tracking in Google Analytics 4 so you can know which marketing channels are driving the most form submissions (i.e. leads).

In GA4, it's actually not possible or necessary to set up form submission conversion tracking to fire on the "thank you" page. GA4 has what's called "[Enhanced event measurements](https://support.google.com/analytics/answer/9216061?hl=en&ref=freak.marketing)" which will automatically fire 2 events for your HTML form:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64434dc56d9af53e0d333376_CleanShot-2023-03-09-at-09.23.25%402x-1.jpeg)

You can then toggle to "Mark as conversion" in GA4 > Events:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64434ec67e177fb1c02e5b56_CleanShot-2023-03-09-at-09.31.21%402x.jpeg)

This should work regardless if your form is redirecting to a "thank you" page or not.

If for whatever reason it's not working on your website, then you'll probably need to setup some special conversion tracking with Google Tag Manager to trigger when a website visitor hits your "thank you" page or when somebody clicks the form submit button.

[Form icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/form?ref=freak.marketing)

‍
