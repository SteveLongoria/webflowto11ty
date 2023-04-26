---
f_featured: true
f_color: hsla(0, 0.00%, 0.00%, 1.00)
title: Tracking GoDaddy Website Builder Form Submissions as Conversions
f_post-summary: >-
  You have a brand new website built with GoDaddy's Website Builder, but now
  you're wanting to track form submissions as a conversion in Google Analytics
  4. You're not quite sure how you're supposed to go about that since your web
  form doesn't redirect to a "thank you" page.You're used to setting up
  conversion tracking in Universal Analytics where all you need to do is add the
  URL of the thank you page to create a goal. Unfortunately, that's not possible
  with your website built with GoDaddy Website Builder. That is also not how
  Google Analytic 4 works.
slug: godaddy-website-builder-form-submissions-conversions
updated-on: '2023-04-22T03:01:53.087Z'
created-on: '2023-04-18T19:44:08.278Z'
published-on: '2023-04-22T12:56:55.384Z'
f_tags:
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
  - cms/tag/godaddy.md
layout: '[post].html'
tags: post
---

You have a brand new website built with GoDaddy's Website Builder, but now you're wanting to track form submissions as a conversion in Google Analytics 4. You're not quite sure how you're supposed to go about that since your web form doesn't redirect to a "thank you" page.

You're used to setting up conversion tracking in Universal Analytics where all you need to do is add the URL of the thank you page to create a goal. Unfortunately, that's not possible with your website built with GoDaddy Website Builder. That is also not how Google Analytic 4 works.

What to do? Fortunately, Google Analytics 4 has what are called "[enhanced event measurements](https://support.google.com/analytics/answer/9216061?hl=en&ref=freak-marketing)".

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64434dc56d9af53e0d333376_CleanShot-2023-03-09-at-09.23.25%402x-1.jpeg)

GA4 Enhanced Event Measurement for Form Submissions

By default, GA4 will recognize most form submission events on most websites. To track them as a "conversion", it's simply a matter of going into your event settings in GA4 and click the "Mark as conversion" toggle to track any given event as a "conversion".

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64434dc567887f5e6211aa14_CleanShot-2023-03-14-at-11.14.25%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64434dc5c6bbb13f35dd04ed_CleanShot-2023-03-14-at-11.17.15%402x.jpeg)

With that said, I noticed that GA4 was only showing the "form\_start" event firing for the GoDaddy Website I was working on. It wasn't showing "form\_submit" event when the form was actually submitted.

It may just be a bug with GoDaddy Website Builder but if you're really wanting to track form completions it might be best to use a different website builder like Webflow ([affiliate link](https://webflow.grsm.io/4623107?ref=freak.marketing)).

‍
