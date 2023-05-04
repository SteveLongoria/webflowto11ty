---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  Google Ads Call Conversion Tag is only for tracking calls from visitors who
  manually dial the number from viewing the number on their websiteIt doesn't
  track conversions from people who click the phone number to call it on mobile
  devices. This is because it's not tracking clicks at all. It's able to track
  the conversion because each Google Ad visitor sees a different Google
  Forwarding Number, that when called, forwards to your business number.
title: Tracking 'Click to Call' and Manually Dialed Calls as Google Ad Conversions
slug: click-to-call-and-manually-dialed-calls-conversions-google-ads
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/conversion-tracking.md
  - cms/tag/phone-calls.md
  - cms/tag/search-engine-marketing.md
  - cms/tag/lead-generation.md
updated-on: '2023-04-26T18:54:01.788Z'
created-on: '2023-04-26T18:54:01.788Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

Google Ads Call Conversion Tag is only for tracking calls from visitors who manually dial the number from viewing the number on their websiteIt doesn't track conversions from people who click the phone number to call it on mobile devices. This is because it's not tracking clicks at all. It's able to track the conversion because each Google Ad visitor sees a different Google Forwarding Number, that when called, forwards to your business number. This is all great, but you also want to be able to track visitors who click on your phone number on your website. Since the phone number format in the hyperlink is likely different from the phone number displayed on your site, you'll want to set up 2 different Google Tag Manager tags to track these 2 different conversion scenarios.1. The first one is set up using the 'Google Ads Website Call Conversion Tracking' tag. This will dynamically replace your phone number on your website with a Google Forwarding number so we'll be able to track anyone who manually dials the number from viewing the web page on their laptop or desktop computer as a conversion.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644973043f9bedad531b88ba_gtm1.jpeg)

Make sure the phone number format you enter matches the phone number format on your website. So if your phone number is (888) 234-5555, you'll want to make sure you enter (888) 234-5555 and not say 888-234-555.You get the Conversion ID and Conversion Label from Google Ads when creating a new conversion.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/6449730431b2e37e613e8012_gtm2.jpeg)

2\. Next we'll want to set up a tag for when somebody clicks on the phone number. Go ahead and create another Google Ad conversion for this and set up a new tag in Google Tag Manager:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64497304cbec5268cfa8f117_gtm3.jpeg)

Here's how I set up the triggers for this tag:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/6449730498282c57989a090e_gtm4.jpeg)

And for this client I was also tracking clicks on a footer link with the text "Call us" that also initiates a phone call when clicked.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644973041dbfb062d9caad2b_gtm5.jpeg)

After that, just make sure you have the 'Conversion Linker' tag set up to trigger with all page views:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64497305821df748baa069ad_gtm6.jpeg)

That's it! Preview your changes in Google Tag Manager to make sure everything is firing and then publish changes.Now you'll be tracking clicks on the phone number AND the phone number will be dynamically replaced for those who manually enter the number into their phone from viewing the website on their desktop or laptop computer.

‍
