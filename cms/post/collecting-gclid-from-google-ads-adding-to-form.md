---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  If you're reading this, it means you're probably trying to set up offline
  conversion tracking for your Google Ads campaign. It allows you to track
  offline sales conversions in your Google Ad campaign.This makes it easier of
  course to optimize your ad campaign to increase your return on ad spend by
  giving you cost per offline sale data instead of just cost per call/form
  submission data.
title: Collecting GCLID From Google Ads Visitor & Adding To Hidden Form Field
slug: collecting-gclid-from-google-ads-adding-to-form
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/conversion-tracking.md
  - cms/tag/search-engine-marketing.md
updated-on: '2023-04-27T23:36:27.136Z'
created-on: '2023-04-27T23:36:27.136Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

If you're reading this, it means you're probably trying to set up [offline conversion tracking](https://freak.marketing/post/google-ad-offline-conversion-tracking-return-on-ad-spend/) for your Google Ads campaign. It allows you to track offline sales conversions in your Google Ad campaign.

This makes it easier of course to optimize your ad campaign to increase your return on ad spend by giving you cost per offline sale data instead of just cost per call/form submission data.

Visitors who come to your website by clicking on your Google Ad are tagged (I'm assuming you already have [enabled Google Ads auto-tagging](https://support.google.com/google-ads/answer/3095550?hl=en&ref=freak.marketing)) with a unique ID called the GCLID, which I believe stands for 'Google Click ID'. The GCLID string of random letters and numbers that makes a unique ID for that visitor. It's found in the URL when they click over to your landing page and looks something like this:

yourdomain.com?gclid=sod8sd0923sdfoij392092jsdflkje

Now the goal here is to get that GCLID into a hidden form field in the form and so if the Google Ad visitor fills out the form, their unique GCLID will be passed along with their info into your sales CRM.

The trick then is how to grab this unique GCLID data found in the URL (i.e. [query string parameter data](https://en.wikipedia.org/wiki/Query_string?ref=freak.marketing)) automatically when the page loads and put it into the hidden form field.

Welp, you'll need a little bit of Javascript to make this happen.

Here's the code that I use for this:

<script>  
var urlParams = new URLSearchParams(window.location.search);  
const gclid = urlParams.get('gclid');  
document.getElementById("gclidInput").value = gclid;  
</script>

This code assumes the ID on the hidden form field element is 'gclidInput'.

**Note**: Keep in mind that the GCLID query string data disappears if they visit another page of your website, so this will only work if the landing page also has the form they'll be submitting.

If you're driving traffic to a multipage website with a contact page and the Google Ad visitor has to leave the landing page to submit the form, then you'll need a bit more Javascript and that's the topic of another post.

‍
