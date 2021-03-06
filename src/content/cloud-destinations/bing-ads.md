---
collectionKey: cloud-destinations

navText: Microsoft Advertising

path: '/cloud-destinations/microsoft-advertising/'

tags: [cloud, destinations]
---

# Microsoft Advertising

MetaRouter makes it easy to send your data to Microsoft Advertising. Once you follow the steps below, your data will be routed through our platform and pushed to Microsoft Advertising in the appropriate format.

## What is Microsoft Advertising and how does it work?

Microsoft Advertising is a pay-per-click search engine tool that engages customers searching for and looking at your products and services on Bing, Yahoo, and MSN. This network spans millions of unique searchers all over the world, but you can target specific users by city, country, or distance. Ads can also be configured to prompt users to call you or visit your site as soon as they see an ad or perform a certain action. If you're already using another product like Google Ads, it's easy to import that campaign directly into Microsoft Advertising.

Cost-wise, Microsoft Advertising is both exceptionally accessible and adaptable to your needs. They charge per click without a minimum fee and allow you to adjust your budget at any time depending on your team's business needs.

[Learn more about Microsoft Advertising](https://secure.bingads.microsoft.com/).

## Why send data to Microsoft Advertising using MetaRouter?

With MetaRouter, send page and event data to Microsoft Advertising without having to edit code. Once you enable our pipelines, our script will immediately load on your website to start collecting page views and recording events. Events that have a `value` or `revenue` property directly translate to Microsoft Advertising' event value.

## Getting Started with Microsoft Advertising & MetaRouter

Microsoft Advertising will record all of your page views and events sent via `page` and `track`, giving you access to data that you can use to create custom goals and conversions directly on Microsoft Advertising.

**Note:** Microsoft Advertising is available as a client-side destination only.

### Microsoft Advertising Side

To set up your pipeline, you'll need to create your Universal Event Tracking (UET) **Tag ID**. This tag will help you track campaign performance by counting unique conversions and letting you associate multiple conversion goals under a single account.

To do so, first create an account and make a campaign. Here, you'll also have the option to import a Google AdWords campaign.

![bing-ads1](/images/bing-ads1.png).

Once you create a campaign, you'll be taken to your **Campaign** page. On the left sidebar, click on **Conversion Tracking > UET Tags**.

Now, go ahead and create a UET Tag by choosing a name and description.

![bing-ads2](/images/bing-ads2.png).

If you click on **View Tag**, you'll be able to see both the JavaScript code and the 7-digit **Tag ID**. With that, jump over to your MetaRouter dashboard to activate your pipeline directly from our UI.

![bing-ads3](/images/bing-ads3.png).

For more help on getting Microsoft Advertising set up, check out [this Microsoft Advertising support page](http://help.bingads.microsoft.com/apex/index/3/en/56705).

### MetaRouter Side

If you're ready with your **Tag ID** at hand, go ahead and log into your MetaRouter dashboard.

Add Microsoft Advertising as a destination. From there, give your connection a unique name and input your **Tag ID** where prompted.

![bing-ads4](/images/bing-ads4v2.png)

Now, just click on Save to activate your pipeline.

That's it! Get ready for insights.
