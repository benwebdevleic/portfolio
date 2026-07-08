---
layout: case_study
title: "Customer support website"
description: "Designed, tested and delivered a customer support website for a suite of native apps"
order: 6
published: true
---
## 📖 Background

This project was carried out for a publishing company producing digital magazines, read through dedicated iOS and Android apps. The development team had a backlog of bugs they were working through, and resolving them was taking time. In response, the business wanted a support website as a stop-gap — somewhere customers could resolve issues themselves while the apps were improved.

## ⚠️ Problem

Customers were contacting support to resolve issues that could easily have been solved within the app itself.

Support was outsourced to a third party who often took several days to respond, which compounded the problem. Customers were left frustrated by the experience and, in some cases, cancelled their subscriptions as a result.

The business was also billed per support request regardless of outcome, so it was paying a premium for a support experience that was actively damaging retention.

## 🎯 Goal

Reduce the number of support tickets raised.

## 🤔 What did we do?

The key stakeholder favoured a well-established solution rather than reinventing the wheel: a support website with instructional articles customers could use to resolve common issues themselves. I took this as the starting brief, but treated the detail of how it should work as something to establish through research rather than assumption.

## 👨🏻‍💻 Competitor analysis

I reviewed a number of existing support systems to understand typical functionality and patterns, then sketched out how I thought our site should be structured. This shaped the core components — most-viewed articles, browse by category, and search — as the backbone of the design.

## 🎨 Prototype

Working from the sketches, I built a mid-fidelity prototype as a Jekyll static site rather than in Figma. That decision took a few extra days upfront, but it was a deliberate trade-off: it let us test real interactive behaviour, particularly the search feature, rather than relying on a simulated version that might have hidden usability issues until launch.

![Gardeners World support website prototype]({{ "/assets/images/gw-support.png" | relative_url }})

## 🔎︎ Usability testing

I designed and ran a round of usability testing to catch problems we hadn't anticipated, recruiting participants who were staff members with no affiliation to the team or product, to keep results unbiased by familiarity with it.

The findings were revealing. Several key parts of the flow went unnoticed by participants — most significantly the most-viewed articles list, which held the answer to the task we'd set them.

One participant with a dyslexia diagnosis explained that the links were hard to distinguish from one another; they registered only as a block of blue and were skipped over. We'd removed the bullet points at the start of each list item, on the assumption that pulling text closer to the left edge would make it faster to scan — but the change had made the links harder to parse, not easier. Reinstating the bullets resolved the issue immediately. It was a useful reminder that a plausible design rationale still needs to be checked against how real users actually read the page.

## 💅🏻 Refinements

I revised the prototype based on what testing surfaced, and it went on to become the finished product. Participant feedback during testing — comments like "it looks functional, but it needs to be" — reinforced the core design principle I was working to: this was a tool for finding the right information quickly, not a product to be admired.

I also built in the ability to brand the site dynamically depending on which magazine app a customer had arrived from, surfacing the relevant logo and brand colours, and passed device and app version data straight through to the "raise a ticket" form to remove unnecessary back-and-forth with support.

## 🏁 Conclusion

Within three months, I'd taken the project from research through to a fully working, usability-tested support website, with features designed to help customers self-serve and to smooth the journey when they still needed help.

The original goal was to reduce support ticket volume, and — notably — it didn't move significantly. Through follow-up conversations, I learned that customers largely preferred speaking to a person over finding the answer themselves; being told which buttons to press felt easier and more reassuring than the effort of searching, even when the information was readily available.

That's a useful finding in its own right, and I don't think it generalises to every audience. If I ran this project again, I'd build in research with customers about their existing support expectations and behaviours before committing to a "common approach" solution, rather than validating the approach only after it had been built.