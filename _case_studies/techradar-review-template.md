---
layout: case_study
title: "TechRadar.com review template"
description: "Discovery research to define an improved product review template"
order: 3
published: true
---
## 📖 Background

The business chose to re-platform all of its premium sites so each could be maintained far more effectively through a single platform, sharing infrastructure across sites and reducing running costs.

Previously, each site had been built with unique layouts, so the business needed standardised layouts that could work across all of them. A review of a smartphone on TechRadar and a review of a coffee machine on T3, for example, would need to share the same underlying review template.

## 🎯 Goal

Produce a responsive review template for product reviews, usable across multiple product types.

## 📝 Approach

There was no existing user insight to draw on within the business beyond secondary research found online — decisions up to this point had been driven by assumption and speculation rather than evidence, and I saw establishing a research-led foundation as a core part of what this project needed to deliver.

With review pages across the business carrying a large amount of product information, I set out to identify which information was actually useful to users, and to understand how that priority should shape what appeared where in the template — rather than treating "more information" as inherently better.

## 👨🏻‍💻 Competitive analysis

I reviewed competitor review layouts to understand the kind of information and visual conventions users would already expect when landing on a product review site, giving me a baseline to test against rather than starting from a blank page.

## 🎨 Mock-up

I built a custom JavaScript library to produce a responsive mock-up of the layout with relative ease, drawing on both the competitive analysis and domain knowledge from the editorial teams.

This wasn't intended as a finished design — I treated it explicitly as a working hypothesis, built specifically to be pressure-tested and iterated on through user research rather than refined in isolation.

## 👥 In-depth interviews, including a card sort task

I designed and ran a guerrilla-style research study in a cafe. To reach a varied pool of participants quickly, I arranged for a temp recruited through a local agency to approach members of the public with a set of screener questions I'd written, armed with a clipboard.

Each session opened with a few questions about the participant's most recent phone purchase, giving me context on what they valued in a smartphone before testing anything.

I then ran a card sort task, asking each participant to identify the five most important pieces of information they'd need to decide whether a phone was worth buying, and separately the five least useful — giving me a clear read on both what mattered and what didn't, rather than just a single ranked list.

Participants were then shown the mock-up and asked to locate the five pieces of information they'd just told me were most important. This surfaced, very quickly, exactly where the design was failing to serve their priorities. I ran this part of the session on a laptop with a webcam, using Camtasia to capture screen activity, audio, and the participant on video simultaneously — giving me a complete record to draw on during analysis.

## 🏁 Summary and reporting

I coded participant responses into four categories — positives, negatives, observations, and recommendations — to keep the analysis structured and comparable across sessions.

For the card sort task, I built a scoring system: 5 points for the most important card down to 1 for the fifth, with an inverted scale applied to the least-useful cards. Totalling scores across every session produced a clear, prioritised list of what users actually needed to see:

![Card sort results]({{ "/assets/images/card-sort-results.png" | relative_url }})

I used these findings to refine the mock-up, which the UI Designer then took forward into the final template design.

I then ran a session with the development team, Tech Lead, Product Lead, and UI Designer to walk through the findings and the resulting design — giving the development team the user context behind *why* the template needed to be built the way it was, not just a spec to implement.

## 💥 Outcome

This project gave the business its first real evidence base for review page design, and delivered a user-centred template as a result. By deliberately excluding information users had told us they didn't need — arguably as important a decision as what to include — the new template carried significantly less clutter than its predecessor.

In the analytics phase following launch, engagement held steady and increased in some sections of the site.

The clearest gains were on mobile: the redesigned layout was a substantial improvement on the previous experience, which had lived on a separate `m.techradar.com` platform:

![Refreshed TechRadar]({{ "/assets/images/refreshed-techradar.png" | relative_url }})

Beyond the design itself, this project gave the wider development team a clearer sense of direction. I took the initiative to break the template down into individual JIRA development tasks and wrote a spec for each one myself — going beyond what the role strictly required. That level of detail was well received by the development team, and it went on to become the standard expected of spec-writing for tasks that followed.