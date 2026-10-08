---
title: "haz_do callout: happy"
date: 2026-10-08T12:20:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type happy."
  desc_long: "Happy callout with a smile icon. Same yellow as tip, caution, and sad. Samples cover a title, no title, and Markdown in the body."
---

Type **happy**. Smile icon. Same yellow as tip, caution, and sad.

{{< haz_do add="callout" type="happy" title="Happy" >}}
This worked, and it is worth a smile.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="happy" >}}
This happy callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="happy" title="With Markdown" >}}
The deploy **finished**.

- site is up
- cache is warm
{{< /haz_do >}}
