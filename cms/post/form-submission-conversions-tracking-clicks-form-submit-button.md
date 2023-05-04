---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  Sometimes the web form you're wanting to track as a conversion doesn't send
  visitors to a 'thank you' page. This is a problem because that's probably how
  you normally track form submission conversions!In the past, I have gotten
  around this by tracking clicks on the form submission button as a
  conversion.This can work fine but can have some problems:
title: >-
  Tracking Form Submission Conversions by Tracking Clicks on The Form's Submit
  Button
slug: form-submission-conversions-tracking-clicks-form-submit-button
f_tags:
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
updated-on: '2023-04-29T20:53:39.120Z'
created-on: '2023-04-29T20:53:39.120Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

Sometimes the web form you're wanting to track as a conversion doesn't send visitors to a 'thank you' page. This is a problem because that's probably how you normally track form submission conversions!

In the past, I have gotten around this by [tracking clicks on the form submission button](https://freak.marketing/track-button-clicks-using-google-tag-manager-google-analytics-4-ga4/) as a conversion.

This can work fine but can have some problems:

1.  Setting up the conversion tracking based on form submit button clicks is sometimes people don't fill out the entire form and click the submit button, which if you're tracking clicks on that button as a form submission conversion, it'll falsely report that as a conversion.
2.  Also, sometimes the client might change the text on the submit button, which can break your conversion tracking.

Instead, I've been [setting up form submission conversion tracking this way using Google Tag Manager](https://freak.marketing/track-form-submissions-as-conversions-without-thank-you-page/).

It isn't 100% perfect either. I've seen some websites trigger a general form submission on just entering data into a field in the form or from clicking on other elements on the website. So when setting it up [this way](https://freak.marketing/track-form-submissions-as-conversions-without-thank-you-page/), you have to be cautious and make sure you set it up correctly so you're not getting bad form conversion data.
