---
layout: post
title:  "Making \"Goadrich Facts\""
date:   2019-11-02 22:52:13
categories: jekyll update
---

Was the Kahn Academy tutorial adequate training, or were the other elements you needed to succeed? What was frustrating about combining the APIs? What was exciting to get working?

When Jack and I started work on the [Goadrich Facts][goadrich-facts], we first looked at the Kahn Academy tutorial. However, instead of doing it all at once, we worked on a single part of the the lesson, then used that info to make progress on the site. Coincidentally, whenever we were stumped on site problems, the next tutorial tended to have the answer to have them.

Combining the APIs was surprisingly easy. We used Dicebear Avatars and the ICNDB (Internet Chuck Norris Database), both of which had very clear and easy to use APIs.
 
Dicebear returned a unique avatar simply by setting a URL containing a seed string near the end as the src for an img HTML tag, greatsly simplifying the way the code looks in the end.

The ICNDB was a bit tougher, but once we extracted the data from the JSON output, it wasn't too tough to put the jokes into the HTML. Something we noticed in the API is that we could filter to only "nerdy" jokes, as well as change the name used. Using this, we decided to make our site an homage to the best CSCI 340 teacher we've had.

Of all the things I enjoyed completing, managing to append entire new chunks of HTML code as new robots/facts, then moving recursively through each of those generated tags was both challenging and fulfilling.

[goadrich-facts]: https://privateeye421.github.io/Goadrich-Facts/