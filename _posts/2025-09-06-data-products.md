---
layout: post
title: "The Benefits Of Data Product Thinking"
description: Streamline your efforts
image: assets/images/mountains-192987_1280.jpg
author: Connor Quinn
categories: [databricks, data value, data products, governance]
permalink: /data-products/
related_posts:
  - /datavalue/
---

To my mind, the shift of focus to data products in recent years is a response to the fact that very few businesses feel they are being well served by their data. Data becomes a costly and time consuming effort that is rarely at the heart of how the business makes decisions.

Adopting a data product mindset aims to shift the focus to what will be most valuable to users. Making decisions about how best to manage, clean, curate, and serve data becomes simplified when the users are treated as the highest priority.

### What is a data product and what is not a data product? 

Im my experience, there is a lot of confusion about data products. This is because the focus on data products might not change much about the underlying data. You might still have the same facts and dims underpinning a report, or the same ML model underpinning a prediction. 

The benefit of data teams thinking in terms of data products is that it focusses all of our decision making on making that product successful to the people who will use it.

In this view of the world, an engineer who onboards 50 datasets to a platform does not have 50 data products. That is because those 50 datasets are not organised around the business and business users. Those datasets only become a data product when they are brought together to serve a clear use for a customer.

### The importance of Data Product Owners

A common pitfall when building data products is to skip the step of agreeing a data product owner. Usually that is because the existing org structure doesn't have a role fitting this description and so instead, the job is fobbed off to someone already up to their eyeballs with work. Finding the right person to engage with the business is hard, and so there is a temptation for the data teams to name something a data product and then send it out into the world without clear ownership. 

This is a mistake.

Let's return to the example of a data engineer 'owning data products' above. When the dataset is onboarded, the 'data product owner' needs to make a decision about the data quality requirements of that data. The data engineer fundamentally cannot make an informed decision about this because they are not closely involved with the end users and do now understand how the data will be used.

The consequence of not having a data product owner who is aligned with the business will be that data teams make well-intentioned but poorly informed decisions about the data, while the business becomes increasingly removed. Back to the common pattern of the data team working hard but the business being left unsatisfied.

The data product owner should sit between the business and the data teams, guiding priorities according to what will add most value for users. Their overriding concern should be **what will make our users happy**. They are accountable not only for the delivery of the product, but also for publicising it, making it discoverable, monitoring its use and performance, and working to align the semantics across the wider business. 

One final key aspect of the role is knowing when to retire a data product. By shifting to a data product mentality means that we should have clear vision of how well the product is being used by the business. When the product stops justifying its existence, the product owner should decide to turn it off. Finally your data can have a lifecycle where the burden does not only ever increase.

--- 

It can be difficult for teams to break out of established ways-of-working without some extenal support. At Kelvin Analytics, we can partner with your data leaders and delivery teams to establish data product thinking and ways of working that your teams can carry forward. 

[Learn more about how we can support your data strategy]({{ '/data-strategy/' | relative_url }})

Check out this excellent blog post: [Building high quality data products](https://www.databricks.com/blog/building-high-quality-and-trusted-data-products-databricks).



