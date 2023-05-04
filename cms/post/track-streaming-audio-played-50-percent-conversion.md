---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  You have a website featuring one audio file streaming on the page and you're
  wanting to drive more engagement, more 'plays' for this audio file by using
  PPC advertising like Google Ads.The problem is, you're not sure how to track
  audio streams as a 'conversion'. Without having that setup, it'll be difficult
  to see which ad channels and which keywords are generating the most 'plays' on
  your audio file.I recently had this issue while setting up a Google Ad
  campaign to help a friend promote his band. We're trying to drive more
  engagement with his band and get more people listening to their music.
title: Track Streaming Audio Played 50% or More as a 'Conversion'
slug: track-streaming-audio-played-50-percent-conversion
f_tags:
  - cms/tag/google-analytics.md
  - cms/tag/conversion-tracking.md
updated-on: '2023-05-01T04:03:30.959Z'
created-on: '2023-05-01T04:03:30.959Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

You have a website featuring one audio file streaming on the page and you're wanting to drive more engagement, more 'plays' for this audio file by using PPC advertising like Google Ads.

The problem is, you're not sure how to track audio streams as a 'conversion'. Without having that setup, it'll be difficult to see which ad channels and which keywords are generating the most 'plays' on your audio file.

I recently had this issue while setting up a Google Ad campaign to help a friend promote his band. We're trying to drive more engagement with his band and get more people listening to their music.

So the first step was to create a landing page with an html5 audio element for streaming a song. After the landing page was done, I installed Google Tag Manager to set up conversion tracking on the audio file.

I used [this script](https://www.thyngster.com/tracking-html5-videos-gtm/?ref=freak.marketing) and just swapped out 'video' with 'audio' as they explain in [this blog post](https://www.analyticsmania.com/post/track-html5-audio-player-with-google-tag-manager/?ref=freak.marketing). I followed the rest of the steps in that tutorial as well except instead of just tracking when somebody starts playing the audio file, I set up the trigger to fire only when somebody has listened to at least 50% of the audio file or more. You could easily set this to 60%, 70%, etc.

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644f39d8057e88466e967e70_CleanShot-2022-08-26-at-10.38.34%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644f39d8f48193f12b659166_CleanShot-2022-08-26-at-10.39.16%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644f39d81770ff2aa4e7dee1_CleanShot-2022-08-26-at-10.39.37%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644f39d830aff1349480459c_CleanShot-2022-08-26-at-10.39.57%402x.jpeg)

![](https://uploads-ssl.webflow.com/643ef3037ed557253b9bbcfe/644f39d8352fddebaa15407a_CleanShot-2022-08-26-at-10.40.10%402x.jpeg)

I only have the conversion tracking set up for GA4 but once we start the Google Ad Campaign I can set up a tag for Google Ad Conversion Tracking or just import the GA4 goal.

‍
