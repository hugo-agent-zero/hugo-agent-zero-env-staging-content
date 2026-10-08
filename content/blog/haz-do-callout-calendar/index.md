---
title: "haz_do callout: calendar"
date: 2026-10-08T13:00:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type calendar."
  desc_long: "Calendar callout with a calendar-check icon. Same grey as note and deadline. Samples cover a title, no title, and Markdown in the body."
---

Type **calendar**. Calendar-check icon. Same grey as note and deadline.

{{< haz_do add="callout" type="calendar" title="Calendar" >}}
Office hours are Tuesday and Thursday.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="calendar" >}}
This calendar callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="calendar" title="With Markdown" >}}
Next review is **Thursday**.

- bring the draft
- leave the assets
{{< /haz_do >}}
