---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  You have a Google Ad Campaigns set up and it's generating call conversions;
  calls that lasted over 60 seconds, or whatever length of time you set. The
  problem is, you don't know which calls are leading to actual offline sales
  conversions. You're only able to see calls that lasted over X seconds long.You
  don't even get a name or phone number for the call conversion. You only know
  that it happened.You know Google Ads has offline conversion tracking, but
  you're not sure how the hell it works. You've read about something called the
  'GCLID' but it's all greek to you.Do you even need the GCLID for offline
  conversions coming from a phone call?
title: Tracking Offline Conversions from Phone Calls in Google Ads
slug: tracking-offline-phone-call-sales-conversions-in-google-ads
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/phone-calls.md
  - cms/tag/conversion-tracking.md
updated-on: '2023-04-29T21:39:29.888Z'
created-on: '2023-04-29T21:39:29.888Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

You have a Google Ad Campaigns set up and it's generating call conversions; calls that lasted over 60 seconds, or whatever length of time you set. The problem is, you don't know which calls are leading to actual offline sales conversions. You're only able to see calls that lasted over X seconds long.

You don't even get a name or phone number for the call conversion. You only know that it happened.

You know Google Ads has offline conversion tracking, but you're not sure how the hell it works. You've read about something called the 'GCLID' but it's all greek to you.

Do you even need the GCLID for offline conversions coming from a phone call?

Do you need special software to track the offline conversions from phone call?

The answer to both of those questions is no. You see, Google Ads tracks offline conversions differently depending on if the lead came in via phone call or form submission.

For form submissions, you need to collect the GCLID but not with phone calls.

For phone calls, the unique identifier is just the user's phone # they called in on. That's how Google connects the dots later when you upload your CRM conversion data into Google.

So first, you need to start collecting the following data for each phone call lead:

Caller's Phone Number  
Call Start Time

Then if they become a customer, you need to the following:  
  
Conversion Name  
Conversion Time  
Conversion Value  
Conversion Currency

You can keep track of this data in a CRM, Google Sheet or Airtable. You'd then need to import this data into Google Ads regularly. [Here's a template Google offers](https://docs.google.com/spreadsheets/d/1T1kh6koOeoPxww20s3aRYv6jZhW70O2ZG9ciyx6H7iU/edit?ref=freak.marketing#gid=1008980182) so you can see what they're looking for.

The [Zapier Zap](https://support.google.com/google-ads/answer/9837650?hl=en&ref=freak.marketing) only deals with offline conversions from leads that submitted a form (along with their gclid), not calls.
