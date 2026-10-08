---
title: "haz_do callout: caution"
date: 2026-10-08T09:40:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type caution."
  desc_long: "Caution callout with a circle-exclamation icon. Samples cover a title, no title, and Markdown in the body."
---

Type **caution**. Circle-exclamation icon. Highest stakes.

{{< haz_do add="callout" type="caution" title="Caution" >}}
This deletes production data.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="caution" >}}
This caution has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="caution" title="With Markdown" >}}
Do **not** run this until you have a backup.

1. Export the data.
2. Confirm the backup restores.
3. Then delete.
{{< /haz_do >}}
