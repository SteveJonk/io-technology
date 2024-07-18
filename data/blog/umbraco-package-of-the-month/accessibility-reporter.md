---
title: 'Umbraco package of the month: Accessibility Reporter'
date: '2024-07-19'
tags: ['umbraco', 'a11y', 'accessibility']
summary: 'A quick look at the Umbraco package Accessibility Reporter, what is it and how does it work.'
authors: ['jeroen-van-kempen']
serie: umbraco-package-of-the-month
---

At Codegarden there was an award show and one of the categories was about the community packages, and while watching it I realised I hadn't heard of most of them. This wasn't because the packages weren't good; I just don't use many of them in my daily work, sticking mostly to Usync, Contentment, and SEO Checker. But seeing the awards made me curious. Why were these packages nominated, and why did Accessibility Reporter win? So, I decided to look into a different package each month to learn more about it and write a short blog post about it. Where else to start than this year’s winner, Accessibility Reporter, made by Matt Begent and Jack Durcan.

## What is it about?

“Accessibility Reporter is an open-source tool integrated into Umbraco for testing your website against the Web Content Accessibility Guidelines (WCAG) to help you make your website accessible.”
Accessibility is the metric that determines how usable your site is for people, specifically for people with any kind of disability who rely on tools and software to help them navigate the internet. It is always a great thing to focus on because it improves the site for every visitor, not just the disabled. This is a topic that has recently been more in the spotlight because of the laws in the EU that will check your website for it but additionally also because Google might be considering it for SEO purposes. But besides these good reasons why your client should want it there is also an even better reason, to support your future customers.

## How does it work?

All you have to do is add the package, build your solution and bang it is ready to be used. On your dashboard there now is a tab called “Accessibility Reporter” and from there you can start the test to check your site. After running the tests you will quickly see the results on how your website compares to the WCAG. If you have a large site or a headless solution you will have to do some more configuration but don’t worry there is documentation for that and is easily set up via the appsettings.
The package is only able to test on a few aspects from WCAG, on each test detail page there is a checklist so you can manually check those aspects. Some examples of those are:

1. tab order;
2. interactive elements can be reached using keyboard controls;
3. interactive elements have a clear focus style.

But there are many aspects that it is possible to detect like:

1. alt text for images;
2. missing or non-unique form labels;
3. color contrast;
4. and many more.

![An overview page showing the statistics of the verious test done by Accessibility Reporter](/articles/umbraco-package-of-the-month/accessibility-reporter/Accessibility_Reporter_overview.png)

![An page where more detail is shown of the error's from the test on a specific tested page](/articles/umbraco-package-of-the-month/accessibility-reporter/Accessibility_Reporter_detail.png)

## Conclusion

In my opinion, Accessibility Reporter is a great package that requires barely any setup for the high impact it can have. It is a great tool to make your client more aware of the issue and a great way to have oversight of the changes that need to happen. Once the site is set up correctly it is a good way to keep the content team informed of the impact of their work. It is a way to create more work for your client and to show that we are proactively working on the improvements of the site.

I would give Matt Begent and Jack Durcan a well-deserved High five you rock 🙏.
