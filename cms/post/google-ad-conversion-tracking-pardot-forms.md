---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I have a client who needed help tracking Pardot iFrame form submissions as a
  conversion in Google Ads and Google Analytics. The form was embedded on their
  site.Unfortunately, you can't use the built-in 'Form Submission' trigger in
  Google Tag Manager for Pardot iFrame form submissions.I also tried the
  suggestion in a blog post here for tracking Pardot iFrame form submissions but
  it didn't work and I don't know enough javascript to debug the script.While I
  was inside the Pardot forms editing the thank you message code, I saw I can
  have the form redirect users to any URL of my choosing after the form has
  been 
title: Google Ad Conversion Tracking for Pardot iFrame Form Submissions
slug: google-ad-conversion-tracking-pardot-forms
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/conversions.md
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
updated-on: '2023-04-30T18:07:25.267Z'
created-on: '2023-04-30T18:07:25.267Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

I have a client who needed help tracking Pardot iFrame form submissions as a conversion in Google Ads and Google Analytics. The form was embedded on their site.

Unfortunately, you can't use the built-in 'Form Submission' trigger in Google Tag Manager for Pardot iFrame form submissions.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eae2f152cad6ccf6301f2_CleanShot-2022-06-04-at-10.50.22%402x.jpeg)

I also tried the suggestion in a blog post [here](https://www.obilityb2b.com/blog/3-ways-to-track-pardot-conversions-in-google-analytics/?ref=freak.marketing#:~:text=In%20Pardot%2C%20go%20to%20Marketing,GTM%20loads%20within%20the%20iFrame.&text=In%20GTM%2C%20create%20a%20Tag,new%20code%20within%20the%20iframe) for tracking Pardot iFrame form submissions but it didn't work and I don't know enough javascript to debug the script.

While I was inside the Pardot forms editing the thank you message code, I saw I can have the form redirect users to any URL of my choosing after the form has been submitted. Well, that certainly will make this easier.

I had the form redirect to a 'thank you' page and tracked that page view as a conversion using Google Tag Manager. Easy peezy!
