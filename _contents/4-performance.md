---
layout: content
title:  "Performance"
permalink: /contents/performance
description: The performance tools that we use
---

We believe that web performance is very important and should always be improved.
Sometimes it can even define if the user will really enjoy and use the application or not.

We use two different tools to analyze and optmize web performance:`Page Speed Insights` and `WebPageTest`.
Both help us to follow the best practices, but the first will be used when we need fast feedbacks
and the second to have more detailed and specific information.

## Page Speed Insights

It was created by Google and is very easy to use.
The first way is paste the **url** of the application that you want to test in the [tool site](https://developers.google.com/speed/pagespeed/insights/)
and the other way is installing the [chrome extension](https://chrome.google.com/webstore/detail/pagespeed-insights-with-p/lanlbpjbalfkflkhegagflkgcfklnbnh).

After that, the tool will give you a score and specific tips to improve it.
You can also see the result for mobile and desktop resolutions.

## WebPageTest

For use it you can also paste the **url** in the [tool site](https://www.webpagetest.org/),
but now you can specify the test location and the browser that you want to test.

After submitting the test, at the top of the results page,
you can see the score for the most critical performance optimizations as compress images, cache static content
or use of CDN.

Right below, you will find a table with important high-level metrics and its results in the first view and repeated view of the page.
One significant metric, mainly for the user, is the **Speed Index**, a measure of how quickly the visible parts of a web page are displayed.

Besides that, WebPageTest provides a waterfall graph showing when each resource was loaded,
a pie chart with the sizes of all resources,
and makes a video showing frames by frame of the page loading.
You can find the whole documentation [here](https://sites.google.com/a/webpagetest.org/docs/).
