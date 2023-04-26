---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  Recently I was trying to figure out a way to send a Typeform Survey to my
  Convertkit (aff link) email subscribers that didn't require them to enter
  their email address once they click over to the Typeform Survey.I wanted to
  pass this data using a query string parameter.This is ideal for UX purposes
  but it's also for functional purposes. You see, I want to store the Typeform
  responses on the subscribers Convertkit profile using the same email address
  they signed up with originally.
title: How to Pass Convertkit Subscriber’s Email Address as a Query String Parameter
slug: pass-convertkit-subscribers-email-address-query-string-parameter
f_tags:
  - cms/tag/convertkit.md
  - cms/tag/email-marketing.md
  - cms/tag/marketing-automation.md
updated-on: '2023-04-22T19:57:58.566Z'
created-on: '2023-04-22T19:57:58.566Z'
published-on: '2023-04-26T03:04:24.119Z'
layout: '[post].html'
tags: post
---

Recently I was trying to figure out a way to send a Typeform Survey to my Convertkit ([aff link](https://convertkit.com/?lmref=nx-ezw&ref=freak.marketing)) email subscribers that didn't require them to enter their email address once they click over to the Typeform Survey.

I wanted to pass this data using a query string parameter.

This is ideal for UX purposes but it's also for functional purposes. You see, I want to store the Typeform responses on the subscribers Convertkit profile using the same email address they signed up with originally.

If I leave it up to them to re-enter their email address in the Typeform survey they may enter a different email address than the one they signed up to Convertkit with. They would now have 2 Convertkit profiles. This just creates a mess.

I asked Convertkit support if they knew how I could achieve this and they sent me [this link](https://help.convertkit.com/en/articles/4446616-automatic-utm-parameters?ref=freak.marketing).

This didn't address my question of course. That article only explains how to add my own custom static UTM parameters. I want to add dynamic query string parameter data based on whatever that subscriber's email address is.

So it would be different data for each subscriber that clicks on the link.

Quick example:

Subscriber A clicks on the link and the query string parameter would be mysite.com/link?email=subscribera@email.com

Subscriber B clicks on the link and the query string parameter would be mysite.com/link?email=subscriberb@email.com

Etc.

Convertkit Support said it wasn't possible yet and to submit the feature request to their team.

Before calling it quits I decided to tinker with liquid templating to see if I could get it to work that way. Fortunately, since Convertkit has support for liquid templating, I got it to work!

You can easily append the subscriber's email address data via query string parameter with the following syntax:

[https://yourdomain.com/link?email=](https://yourdomain.com/link?email=&ref=freak.marketing){{ subscriber.email\_address }}

Now [Typeform will automatically capture their email address from the query string](https://developer.typeform.com/create/hidden-fields/?ref=freak.marketing), and insert that info via a Typeform hidden field. This allows the subscriber to get started with the survey immediately.

**Update:** I actually ended up just using a Webflow Form ([affiliate link](https://webflow.grsm.io/4623107?ref=freak.marketing)) for the survey. Typeform's hidden fields are a premium feature and I didn't feel like upgrading just for that.

‍
