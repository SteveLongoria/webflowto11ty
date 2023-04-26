---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I was recently setting up a new Google Ad campaign for a client and optimizing
  an old campaign they had running for several months.Upon reviewing their
  websites and existing campaigns I noticed they weren't tracking all of their
  conversions. They had a 'Schedule Now' button that sent visitors to a
  SimplyBook scheduling app, which was hosted on a separate domain.
title: >-
  How to Track Button Clicks on Your Squarespace Website Using Google Analytics
  4 (GA4)
slug: track-button-clicks-squarespace-google-analytics-4-ga4
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/google-tag-manager.md
  - cms/tag/conversion-tracking.md
updated-on: '2023-04-25T19:45:47.539Z'
created-on: '2023-04-25T19:45:47.539Z'
published-on: '2023-04-26T03:04:24.119Z'
layout: '[post].html'
tags: post
---

I was recently setting up a new Google Ad campaign for a client and optimizing an old campaign they had running for several months.

Upon reviewing their websites and existing campaigns I noticed they weren't tracking all of their conversions. They had a 'Schedule Now' button that sent visitors to a SimplyBook scheduling app, which was hosted on a separate domain.

Unfortunately, SimplyBook doesn't allow you to redirect the visitors to a URL of your choice after they finish scheduling AND they don't integrate with Google Analytics. This means we couldn't track scheduled appointments as a conversion.

So what's the next best solution without requiring the client to change scheduling apps? Track clicks on the 'Schedule Now' button as a conversion in the Google Ad campaign.

Traditionally I handled this using Universal Google Analytic Events and adding a custom attribute to the HTML button element to track clicks on that button as a Google Analytics Goal. Squarespace doesn't allow you to add custom attributes to HTML elements, however.

That's when I decided to dive into the world of Google Tag Manager (GTM). Until recently I had avoided GTM simply because I hadn't used it much. I didn't see any reason to use it since I typically keep the number of scripts on my website to a minimum and manually inserting a few scripts was easy.

Well here was a reason to use it. With Google Tag Manager it's a lot easier to track clicks on any HTML element. Since this was a new Google Analytics account I also decided to set it all up with Google Analytics 4 (GA4) since that is now the default with new Google Analytics accounts.

[Click Here](https://freak.marketing/post/track-button-clicks-using-google-tag-manager-google-analytics-4-ga4/) to see how to set it all up in 4 easy steps!

‍
