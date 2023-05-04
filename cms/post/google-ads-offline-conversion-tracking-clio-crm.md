---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  I recently had been tasked to help my client set up offline conversion
  tracking for his Google Ads Campaign. They use Clio Grow and Clio Manage, as
  their CRM.The first step is confirming leads are being added to the CRM with
  the correct phone number. Google Ads tracks offline conversions coming from
  calls by using the lead's phone # they called in on as their user ID of sorts.
  It's how Google connects the dots later when you upload offline conversion
  data into your Google Ads account.
title: Setting up Google Ads Offline Conversion Tracking with Clio CRM
slug: google-ads-offline-conversion-tracking-clio-crm
f_tags:
  - cms/tag/google-ads.md
  - cms/tag/conversion-tracking.md
updated-on: '2023-04-29T20:51:49.104Z'
created-on: '2023-04-29T20:51:49.104Z'
published-on: '2023-05-01T19:03:13.631Z'
layout: '[post].html'
tags: post
---

I recently had been tasked to help my client set up offline conversion tracking for his Google Ads Campaign. They use Clio Grow and Clio Manage, as their CRM.

The first step is confirming leads are being added to the CRM with the correct phone number. Google Ads tracks offline conversions coming from calls by using the lead's phone # they called in on as their user ID of sorts. It's how Google connects the dots later when you upload offline conversion data into your Google Ads account.

With form submissions, the unique identifier simply names and email address the lead submitted via the form. It used to be required to capture the GCLID to track offline conversions from form submissions but Google's recently made it easier with something called [Enhanced Conversions](https://support.google.com/google-ads/answer/9888656?ref=freak.marketing#leads), no longer requiring the GCLID.

Now we need to be able to identify when a lead becomes a customer or client, so we can track that data and import back into Google Ads. This can be difficult to determine with some CRMs and the exported data typically needs a lot of cleaning up. This is a lot of work!

Instead, you can set up a [zap using Zapier.com that will import the offline conversion into when a certain event happens in the CRM](https://zapier.com/apps/clio/integrations/google-ads?ref=freak.marketing). Each CRM has a different API and allows for different automation and actions with a different set of 'triggers'.

For Clio, the trigger to use in this case would be when a person contact is added to the CRM. It's important to note that [Clio Grow doesn't have an open API](https://support.clio.com/hc/en-us/articles/360016556413-Does-Clio-Grow-Have-an-API-?ref=freak.marketing). This means Zapier is working with Clio Manage. When a contact is being added to Clio Manage, at that point they are a client/sale. This is why this trigger works.

For other CRMs you might need for the trigger to be when a certain custom field reads 'customer'. There are many different ways to set this up depending on what CRM you're using.

The other thing to note, the [Zapier zap that works with Google Ads](https://zapier.com/apps/clio/integrations/google-ads?ref=freak.marketing) is [only for form submission leads](https://support.google.com/google-ads/answer/9837650?hl=en&ref=freak.marketing). You have to import offline conversions that come from calls differently, via spreadsheet or Google Sheet. For this you can still use a Zapier zap to populate a Google Sheet with offline conversion data coming from calls that you can then sync/import to your Google Ads Account.
