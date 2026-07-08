---
layout: case_study
title: "Radio Times Puzzles"
description: "Turning around a failing new product"
order: 4
published: true
---

## 📖 Background

While at Immediate Media, a new Radio Times Puzzles website launched, offering a subscription to online crosswords. It was a small commercial initiative intended to generate revenue horizontally by giving the existing Radio Times audience a new reason to subscribe.

The site was built on an off-the-shelf CMS with third-party plugins and a common theme, without UX involvement. The team was only brought in once the Site Owner identified a problem they couldn't explain internally.

## ⚠️ Problem

Subscribers were cancelling within their first month. The Site Owner approached the UX team without a clear understanding for why, and asked for help diagnosing the cause.

## 👋 Kick-off

I met with the Site Owner and a developer to scope the problem. Reducing subscriber churn was the agreed goal. Stakeholders had a few ideas they wanted to test, but were ultimately more interested in understanding root cause than jumping to solutions.

## 📈 Approach

I applied the Kano Model to structure the investigation, prioritising the elimination of detractors — the aspects actively damaging the experience — before considering any enhancements. The logic was straightforward: removing the single biggest cause of cancellation would move the churn metric more than any number of incremental improvements, and would do so faster.

To scope the investigation efficiently, I reviewed analytics data before designing the study. Two things stood out: the large majority of users were on mobile devices, and crosswords were by far the most-used puzzle type on the site, despite other formats being available. This let me narrow a broad "why are people churning" question into a focused, testable one: how well does the mobile crossword experience actually perform for real users?

## 🔎︎ Usability testing

I designed a moderated usability study using concurrent think-aloud protocol — participants completed a crossword on their own mobile device while narrating their experience in real time, with their screen shared over video call.

Given the tight timeline and the low-risk, exploratory nature of the study — this was about surfacing an unknown problem, not validating a solution — I recruited a convenience sample of friends and family rather than running a formal recruitment cycle. This was a deliberate trade-off of representativeness for speed, appropriate given the cost and risk profile of the project.

I also chose not to require screen-recording software. Previous projects had shown that installation steps introduce friction that skews recruitment toward more technically confident participants; live screen-sharing over video call kept the sample closer to typical users while still giving me the concurrent visibility I needed.

## 🕵 Findings

The dominant detractor was a small technical fault with an outsized effect: tapping a crossword square to enter a letter triggered a native mobile tooltip that was never intended to appear. Users had to dismiss it before they could type, and it reappeared on every subsequent tap.

For a puzzle requiring dozens of individual letter entries, this turned a minor irritation into a compounding barrier — every single keystroke carried an extra interruption, and several participants found the puzzle became effectively unplayable well before completion. This was a task-completion blocker, not a cosmetic annoyance, and it mapped directly onto the churn window stakeholders were seeing: a broken core interaction in the first weeks of use.

Other smaller issues surfaced during testing, but this one was disproportionately responsible for the frustration participants expressed.

## 👨🏻‍🏫 Outcome

I presented findings back to stakeholders with a clear, prioritised recommendation: resolving the tooltip defect alone should be treated as the highest-priority fix, ahead of any other issue identified, given how directly it linked to the reported cancellation behaviour.

## 🚀 Impact

Addressing the key detractor resulted in a **70% reduction in subscriber churn**. The result validated the Kano-based approach taken at the outset: a single, low-effort technical fix was responsible for the majority of the churn signal, delivering a significant return on a very small engineering investment.