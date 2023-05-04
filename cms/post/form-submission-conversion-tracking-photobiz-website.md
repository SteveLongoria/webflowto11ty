---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I got a new client recently that had his website built with PhotoBiz, which
  honestly I had never heard of before. It never ceases to amaze me how many
  "website builders" there are these days.Anyways, since I was setting up a
  Google Ad Campaign for this client I was wanting to track submissions on his
  Request Quote form as a Google Ad Conversion.The form didn't redirect to a
  'thank you' page, so I was crossing my fingers that I could set it up using
  the Google Tag Manager 'Form Submission' Trigger.
title: Tracking Form Submission Conversions on a PhotoBiz Website
slug: form-submission-conversion-tracking-photobiz-website
f_tags:
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
updated-on: '2023-05-01T18:44:19.686Z'
created-on: '2023-05-01T18:44:19.686Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

I got a new client recently that had his website built with [PhotoBiz](https://photobiz.com/?ref=freak.marketing), which honestly I had never heard of before. It never ceases to amaze me how many "website builders" there are these days.

Anyways, since I was setting up a Google Ad Campaign for this client I was wanting to track submissions on his Request Quote form as a Google Ad Conversion.

The form didn't redirect to a 'thank you' page, so I was crossing my fingers that I could set it up using the [Google Tag Manager 'Form Submission' Trigger](https://freak.marketing/post/track-form-submissions-as-conversions-without-thank-you-page/).

There didn't seem to be anyway to add the Google Tag Manager script globally to the whole site at once, so instead we had to resort to just embedding an HTML element on each page.

Since you can't really specify where you're placing the script, like putting it in the <head> or just below the opening <body>, I wasn't sure if it would work.

It turns out it doesn't matter, Google Tag Manager still worked just by embedding the code on the page using [Photobiz' embed HTML element](https://blog.photobiz.com/growth-hub-blog-posts/embedding-and-getting-creative-with-the-photobiz-html-block?ref=freak.marketing).

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/6450084da832feae24d710e1_20220623131804_384681.png)

I then set up the Google Tag Manager trigger using [the "Form Submission" trigger](https://freak.marketing/post/track-form-submissions-as-conversions-without-thank-you-page/).

After testing in Preview mode, everything was firing correctly! It's been almost 2 weeks into the campaign now and the conversion tracking great!
