---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  Setting up micro-conversion tracking like clicks on buttons can give you
  amazing insights into any campaign. Now that Google Analytics 4 is here, it
  can be tricky for those who have never used it to set up conversion tracking
  on button clicks.Here's how to set it all up in 4 easy steps:Step 1: Set up
  basic GA4 configuration using GTM
title: How to Track Button Clicks using Google Tag Manager & Google Analytics 4 (GA4)
slug: track-button-clicks-using-google-tag-manager-google-analytics-4-ga4
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/google-tag-manager.md
  - cms/tag/conversion-tracking.md
updated-on: '2023-04-26T02:24:28.160Z'
created-on: '2023-04-26T02:24:28.160Z'
published-on: '2023-04-26T03:04:24.119Z'
layout: '[post].html'
tags: post
---

Setting up micro-conversion tracking like clicks on buttons can give you amazing insights into any campaign. Now that Google Analytics 4 is here, it can be tricky for those who have never used it to set up conversion tracking on button clicks.

Here's how to set it all up in 4 easy steps:

**Step 1: Set up basic GA4 configuration using GTM**

After creating a new GA4 property and Data Stream...

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488add5076acdf76954cfb_Screen-Shot-2021-01-26-at-3.35.34-PM.jpeg)

You'll see a Measurement ID:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488adde9c4ba47c65db421_Screen-Shot-2021-01-26-at-3.jpeg)

Copy that and let's open up GTM. Assuming you created a new GTM account and container for your website already, let's go ahead and click on tags and click the 'new' tag button:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488adde37cbd72de6ed7d3_Screen-Shot-2021-01-26-at-3.jpeg)

You can name your tag whatever you want but I named it GA4 Config followed by the Measurement ID we copied from Google Analytics.

For the tag configuration I set it to 'Google Analytics: GA4 Configuration' and don't forget to enter your Google Analytics Measurement ID, which you'll see is blurred out in my screenshot here:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488add0c93fa7ff98f7da7_GA4-GTM-Tag.jpeg)

After setting the tag configuration, select 'All Pages' for the trigger then click save to save your new GTM tag.

This basic set up will track pageviews across your entire website now so long as you've installed the GTM code snippet on your site already.

Now, since we're wanting to track clicks on the 'Schedule Now' button as a conversion or goal, we need to go a couple steps further.

**Step 2: Use preview mode in GTM & debug mode in GA4 to identify the element you want to track clicks on**

We need to find out what this 'Schedule Now' buttons' unique identifier is so we can track clicks on the button. This could be an element ID, Class, URL, etc.

Something unique that we can use to tell GTM and GA4 to register conversions when visitors click on the 'Schedule Now' button specifically vs some other random button on the website.

[**This video**](https://youtu.be/JC-hSn1Q3uI) does a good job going through the process of using GTM preview mode and GA4 debug mode to find this unique identifier.

**Step 3: Set up a GTM trigger for this element**

In my case, I used the Click URL of the 'Schedule Now' button as the unique identifier or trigger.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488ade4feedb723a13d4fd_Screen-Shot-2021-01-26-at-3.58.40-PM.png)

Select 'Click - Just Links' as the Trigger Type and under 'This trigger fires on' select 'Some Link Clicks' so we can specify the URL that is unique to this 'Schedule Now' button.

If you don't see the 'Click URL' option you'll want to go into the GTM variables tab and make sure all of the click events are available. Again, [**this video**](https://youtu.be/JC-hSn1Q3uI) does a good job of showing you that step as well.

**Step 4: Set up a GTM tag using this new trigger**

Next step is to head back over to the GTM tags tab and click to create a 'new' tag:

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488adde37cbd72de6ed7d3_Screen-Shot-2021-01-26-at-3.jpeg)

Name it whatever you want, I named mine 'Schedule Now Btn'. For the tag type select 'Google Analytics: GA4 Event'. For the configuration tag, you can reuse the same one we used in step 1.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/64488add0c93fa65348f7da8_schedulenowbtntag.jpeg)

Name the event, this is how it'll show up in your GA4 reports. I simply used 'schedule\_now\_btn'.

For the Triggering, select the trigger we just created in the previous step.

That's it! Now you simply create a conversion around that event in GA4 and import that as a conversion into your Google Ad campaign.

‍
