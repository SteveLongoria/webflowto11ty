---
f_color: hsla(0, 0.00%, 0.00%, 1.00)
f_featured: false
f_post-summary: >-
  So you just set up a sweet new membership site using Memberstack (aff link).
  Now you want to start setting up marketing automation sequences inside
  Convertkit. To do this you need to automatically sync new member data to your
  Convertkit account.If you only have one membership level, this is easy peezy.
  Just use the Memberstack Zapier integration. If, on the other hand, you have
  multiple membership levels, like say Basic, Premium and Gold.
title: How to Integrate Memberstack with Convertkit
slug: integrate-memberstack-with-convertkit
f_tags:
  - cms/tag/convertkit.md
  - cms/tag/membership-site.md
  - cms/tag/email-marketing.md
updated-on: '2023-04-22T03:45:19.961Z'
created-on: '2023-04-22T03:45:19.961Z'
published-on: '2023-04-22T12:56:55.384Z'
layout: '[post].html'
tags: post
---

So you just set up a sweet new membership site using [Memberstack](https://memberstack.io/?ref=freak.marketing) ([aff link](https://memberstack.io/?via=steve&ref=freak.marketing)). Now you want to start setting up marketing automation sequences inside [Convertkit](https://converkit.com/?ref=freak.marketing). To do this you need to automatically sync new member data to your Convertkit account.

If you only have one membership level, this is easy peezy. Just use the [Memberstack Zapier integration](https://help.memberstack.io/post/zapier?ref=freak.marketing). If, on the other hand, you have multiple membership levels, like say Basic, Premium and Gold.

The Memberstack Zapier Integration currently won’t let you specify which plan they’re on. This means you can only tag them as a “Member” inside Convertkit and that’s it. Ideally, you want to be able to tag them based on the membership level they signed up for; Basic, Premium or Gold.

I believe [they're working on this issue](https://forum.memberstack.io/t/zapier-membership-subscribed-to-missing-on-update/141/4?ref=freak.marketing), but in the meantime, you'll have to use a workaround; the [Convertkit Stripe Integration](https://help.convertkit.com/en/articles/2632323-stripe-integration?ref=freak.marketing).

Once you integrate your Stripe account with your Convertkit account, you can then tag and set up automations based on which membership level they're subscribed to.

You may be wondering, “_Well can't I just use the Convertkit Stripe Integration exclusively? Why do I need Zapier?_“

The reason you need both at the moment is because the Convertkit Stripe Integration won't send over all of the custom field attributes you collect from new members upon sign up. Like the customer's first name and last name for example.

To collect all of the custom field attributes you'll need to set up the [Memberstack > Convertkit Zapier zap](https://help.memberstack.io/post/zapier?ref=freak.marketing).

It sucks we can't just use one integration but it is what is for the time being. Either way it gets the job done!
