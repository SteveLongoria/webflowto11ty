---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  One of the most common ways to track form submission conversions is by
  tracking the number of people reach the 'thank you' page after submitting the
  form. This is a fine way to track conversions. I've never had any issues with
  it personally.What happens when you have to set up conversion tracking for a
  form that doesn't redirect to a 'thank you' page and instead just shows a
  message on the page they submitted the form from.
title: How to Track Form Submissions as Conversions Without a "Thank You" Page?
slug: track-form-submissions-as-conversions-without-thank-you-page
f_tags:
  - cms/tag/conversion-tracking.md
  - cms/tag/forms.md
  - cms/tag/advertising.md
updated-on: '2023-04-28T22:56:53.017Z'
created-on: '2023-04-28T22:56:53.017Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

One of the most common ways to track form submission conversions is by tracking  the number of people reach the 'thank you' page after submitting the form. This is a fine way to track conversions. I've never had any issues with it personally.

What happens when you have to set up conversion tracking for a form that doesn't redirect to a 'thank you' page and instead just shows a message on the page they submitted the form from.

As a freelancer, I come across this quite often. Sure, I could ask the client to redirect visitors to a 'thank you' page after they submit the form but sometimes it's not possible, depending on what type of form solution they're using. Also, it's just not necessary 99% of the time.

Instead, it's easier to just set up conversion tracking with the form by using Google Tag Manager.

Here's how!

Step 1: Make sure you have all of your form variable boxes checked
------------------------------------------------------------------

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644c4ec9b228ee65548e1536_CleanShot-2022-01-10-at-10.09.00%402x.jpeg)

Step 2: Set up a General Form Submission Trigger
------------------------------------------------

This Trigger is for all forms on the site. It's possible to create a trigger for one form specifically but this blog post is showing how to just track all form submissions on the website.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644c4ec9ca821554ae0495aa_CleanShot-2022-01-10-at-10.13.44%402x.png)

Step 3: Create Tag(s) using the new Form Submission Trigger you just created
----------------------------------------------------------------------------

Below screenshots show a tag for Google Ads & Google Analytics using the General Form Submission Trigger we created in Step 2. This would allow you to track form submissions as conversions in Google Ads and as a Goal in Google Analytics. You could also create a tag for Facebook or any other ad platform.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644c4ec930b38d853dfb69b2_CleanShot-2022-01-10-at-10.17.46%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644c4eca84948b15d696b0e7_CleanShot-2022-01-10-at-10.16.43%402x.jpeg)

That's it! You're now all set to track form submissions. If this doesn't work, you may want to consider tracking clicks on the form submission button. You also may have several forms you want to track as separate conversions. [This requires some extra steps that are covered in this blog post](https://freak.marketing/conversion-tracking-for-multiple-forms-without-thank-you-pages/)!

‍
