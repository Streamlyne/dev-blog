---
layout: post
title:  "Newly Designed Asset Profile for Web Dashboard"
date:   2014-04-11
description: |
  Current development on the Web Dashboard, focusing on the Asset Profile.
categories: web
author: glavin

---

---

We have received a lot of very useful feedback from Dawson's trip to the Keyera, Nevis plant.
I'd like to thank all of the Operators for sharing their knowledge and patients.

---

## Asset Profile Layout

After receiving feedback from Operators we have made
many major changes to the Streamlyne Web App,
including the layout of the Asset Profile.
It was expressed that viewing multiple Assets at once may be a common practice.
A potential solution that we developed was to use Tabs for each open Asset,
allowing users to quickly jump back and forth between viewing the Assets they want.

Additionally, we have moved the left side navigation bar inside of the Asset Profile.
This eliminates the confusion of what the items in the left navigation bar represents,
such as `Timeline` and `LOTO and Blinds`.
We hope this is clear that they are to the currently selected Asset,
in this case Asset `PV123` (see image below)

### Screenshot of Asset Profile:
![Asset Profile]({{ site.url }}/assets/images/asset_layout_v2.jpg)

### Questions

We would like to confirm that this Asset Profile layout makes sense
and provides the flexibility desired by Operators.

- Are the active Asset tabs necessary? Can you see yourself using this feature?
Alternatively, users could [open a new Tab in their web browser, such as Google's Chrome](https://support.google.com/chrome/answer/99438?hl=en)
for each Asset.
By letting our Streamlyne Web App handle the tabs,
we actually increase performance of the application.
However, it is more work to develop and maintenance,
so it is important that we know if it is in fact valuable to users.

- Is there any use case that you would like to add?
Multitasking was said to be most important,
however there may be other uses such as a comparison view:
the Assets could display in a split view side-by-side,
enabling users to see two Assets at once.
Would a comparison view valuable, and how often?

---

## Asset Search

We now provide a persistant tab for Asset Search.
This allows for very quick access to Asset's and their related data.

### Screenshot 1:
![Asset Profile]({{ site.url }}/assets/images/asset_search_v2.jpg)

### Questions

- How would you like to search for your Assets?
Currently we are developing support for searching by
Asset name, such as `PV123`, so that you could type in `PV1`
and we would auto-complete with all pressure vessels in the 100 Area, such as `PV123`, `PV145`, et cetera.
Are there any other search queries you would like to make that we should support?


-----

We have many other Asset Profile features that we are currently developing,
which you will see in future posts.
We are going to try and keep these posts short
and give you the opportunity to give us feedback
and share your expertise on various components that make up the whole application.

Looking forward to your comments below! Thank you.
