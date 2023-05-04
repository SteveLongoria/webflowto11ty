---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  You have conversion tracking set up for Google Ads and Google Analytics. Your
  Google Ad Campaign is well underway generating conversions. Everything seems
  to be working out just fine but there's just one problem driving you crazy;
  Google Analytics isn't reporting the same number of conversions coming from
  Google Ads as Google Ads is reporting inside the dashboard (ads.google.com).If
  you're expected to make sound business decisions on where to allocate your
  marketing dollars, you need accurate data on which channels and campaigns are
  driving the best results.
title: Google Analytics and Google Ads Conversion Numbers Aren’t Matching
slug: google-analytics-google-ads-conversion-numbers-arent-matching
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/google-ads.md
  - cms/tag/conversions.md
  - cms/tag/website-analytics.md
updated-on: '2023-04-30T18:02:10.655Z'
created-on: '2023-04-30T18:02:10.655Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

You have conversion tracking set up for Google Ads and Google Analytics. Your Google Ad Campaign is well underway generating conversions. Everything seems to be working out just fine but there's just one problem driving you crazy; Google Analytics isn't reporting the same number of conversions coming from Google Ads as Google Ads is reporting inside the dashboard (ads.google.com).

If you're expected to make sound business decisions on where to allocate your marketing dollars, you need accurate data on which channels and campaigns are driving the best results.

First, you want to check your Google Ad conversion tracking setup. Do you have the following set to 'One' or 'Every'?

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eacecc075ba1883f18c88_CleanShot-2022-05-29-at-11.14.43%402x-2.jpeg)

This can be contributing to the conversion data discrepancy between Google Ads and Google Analytics. Maybe in Google Ads you have the conversion count set to 'One' and in Google Analytics it's counting every conversion.

[Google provides a useful checklist](https://support.google.com/analytics/answer/1034383?hl=en&ref=freak.marketing#zippy=%2Cin-this-article) you go can go over to troubleshoot your set up as well.

Ultimately, the conversion numbers may never match up completely between Google Ads and Google Analytics because they attribute conversions differently.

Here's a quick little example:

1.  A visitor clicks on your Google Ad; doesn't convert
2.  The same visitor 2 days later clicks on Social Media ad or post; doesn't convert
3.  The same visitor 2 days later clicks on an organic search listing; finally converts

In the above scenario, Google Ads will attribute the conversion to the Google Ad Campaign and Google Analytics would attribute it to the organic search channel. If you were running a social media ad for the 2nd touchpoint above, it would attribute the conversion to their channel.

Even if you had both Google Ads and Google Analytics goal/conversion using the same attribution model like 'linear', the numbers still might not ad up due to the differences in how Google Ads and Google Analytics attribute conversions.

As Google states [here](https://support.google.com/analytics/answer/1034383?hl=en&ref=freak.marketing#zippy=%2Cin-this-article) "_Google Ads performs different calculations of the data than Analytics does, so you will see some differences even when the underlying data is the same_."

As a general rule, I use the conversion data provided by the ad platform to optimize ads on THAT platform. When I want to get a fuller picture, comparing multiple different attribution models, I view the model comparison report in Google Analytics.

As the name suggests, this will let you compare results based on different attribution models so you can get a better understanding of how each channel drives results.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eacec8a6c794e103bf07f_CleanShot-2022-05-28-at-10.10.19%402x.jpeg)

In GA4 you can see the model comparison here:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644eacedc59ca610c5b9683c_CleanShot-2022-05-28-at-10.15.33%402x.jpeg)

By comparing different attribution models you should get a better idea of where your marketing dollars and efforts are best used for maximum return on investment.
