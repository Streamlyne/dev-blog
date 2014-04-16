---
layout: post
title:  "Inception of the Scenario Builder"
date:   2014-04-14
description: |
  Operator defined Analytics powered by Streamlyne.
categories: web
author: glavin

---

# Scenario Builder

Written step by steps of Scenarios (Hydrates, Compressor Failure)
Ask Barray to elaborate:
Barry gave the example of barring on a compressor. In a previous plant the compressor engine could measure vibration in two axis, along the axel and perpendicular to the axel. This allowed them to approximate bearing failure within a year. Barry approximate the bearing would fail within the year and while the bosses were out, order a bearing ($25,000 to arrive in a year) on fast track ($50,000 to arrive in 6 months). When his bosses returned he was scolded. His boss was going to cancel the order though Barry argued against, asking how much compressor downtime on this specific line costs per day, $10,000, and stating it was already ordered. The bearing failed in 7 months and they lost only a day downtime ($10,000).
Preface with description: we want to provide a tool for Operators to define Scenarios that Streamlyne will watch for and determine their respective likelihood of occurring. We want to prevent unplanned downtime before it happens.
Should the Scenarios be for a instance in time (State) or chronological events (Sequential)? What do you look for?

What information would you like to see if you are viewing a single Scenario? Cost information?

Would having a quick-reference of all of your Scenarios and graphs of their respective percentage likelihood be valuable?

How often do Asset’s break? What is the most common Asset type that breaks down? What is the most expensive?
What information do you reference from DCS? Can you tell by looking at DCS?
How often does Flaring occur? Is there anything to look for to prevent Flaring? Is that information available via DCS? How much Flaring costs?
Is all of the information for major scenarios, like Hydrates, flaring, valves breaking, plant shutdown, something like that, is all of that information in the DCS, is all of that numbers in the DCS?
How many Scenarios do you expect to have? One or two for every Asset?
