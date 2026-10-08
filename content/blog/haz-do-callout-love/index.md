---
title: "haz_do callout: love"
date: 2026-10-08T12:40:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type love."
  desc_long: "Love callout with a heart icon. Same red as warning and cancel. Samples cover a title, no title, and Markdown in the body."
---

Type **love**. Heart icon. Same red as warning and cancel.

{{< haz_do add="callout" type="love" title="Love" >}}
This one is a favorite.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="love" >}}
This love callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="love" title="With Markdown" >}}
Keep the **short** version.

- one sentence
- one example
{{< /haz_do >}}
