---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  So you have a Ghost blog that's receiving member subscriptions and you want to
  see what traffic sources are generating the most subscribers. You can easily
  do this with Google Analytics and Google Tag Manager.Usually, I set up
  conversion tracking using the general Form Submission trigger in Google Tag
  Manager:Unfortunately, this doesn't seem to work with Ghost's pop-up
  subscription widget.It may just be the theme I'm using, but I think it's just
  how Ghost works.Another way we can set this up is trigger a conversion when
  users are sent to a "thank you" after becoming a subscriber.
title: Tracking Ghost Blog Sign Ups & Subscriptions As a Conversion
slug: ghost-blog-sign-up-subscription-conversion-tracking
f_tags:
  - cms/tag/conversion-tracking.md
  - cms/tag/blogging.md
  - cms/tag/forms.md
updated-on: '2023-05-01T18:46:42.408Z'
created-on: '2023-05-01T18:46:42.408Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

So you have a Ghost blog that's receiving member subscriptions and you want to see what traffic sources are generating the most subscribers. You can easily do this with Google Analytics and Google Tag Manager.

Usually, I set up conversion tracking using the general Form Submission trigger in Google Tag Manager:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/645008e1a832fe2673d74e4d_CleanShot-2023-01-20-at-10.47.19%402x.jpeg)

Unfortunately, this doesn't seem to work with Ghost's pop-up subscription widget.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/645008e1eba755d1e02eadf3_CleanShot-2023-01-23-at-09.51.54%402x.jpeg)

It may just be the theme I'm using, but I think it's just how Ghost works.

Another way we can set this up is trigger a conversion when users are sent to a "thank you" after becoming a subscriber.

Ghost does let you redirect users to a URL of your choice after users subscribe in Settings > Membership > Membership Tiers:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/645008e1b83ae56d7b94aa04_CleanShot-2023-01-20-at-10.50.30%402x.jpeg)

You would have to create a new Ghost page to use as your "thank you" page and enter it in the Membership Tier Settings as shown in the screenshot above.

This works fine if you want to have a "thank you" page. If you don't want a "thank you" page, however, there is another way to set it up.

After somebody subscribes, they're sent an email by Ghost to confirm their subscription. When they click on that link, they're sent back to your website with the added query parameter string "action=signup&success=true".

That's what we're going to set up the trigger around in Google Tag Manager.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/645008e15612d5d8c90d69d9_CleanShot-2023-01-23-at-10.00.14%402x.jpeg)

By default, since the visitor is coming from a link in their email, Google Analytics will probably attribute most conversions to 'email' channel but once you use the model comparison tool to view Position Based Attribution or Linear, you'll should see what traffic sources are generating the most subscribers.

It would be nice if Ghost had a native integration that sent subscription events to Google Analytics for you, but maybe some day!

‍
