---
title: "haz_do callout: deadline"
date: 2026-10-08T13:10:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type deadline."
  desc_long: "Deadline callout with an alarm-clock icon. Same grey as note and calendar. Samples cover a title, no title, and Markdown in the body."
---

Type **deadline**. Alarm-clock icon. Same grey as note and calendar.

{{< haz_do add="callout" type="deadline" title="Deadline" >}}
Copy is due Friday at noon.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="deadline" >}}
This deadline callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="deadline" title="With Markdown" >}}
Freeze the branch on **Friday**.

1. Stop new edits.
2. Tag the release.
{{< /haz_do >}}
