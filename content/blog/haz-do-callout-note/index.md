---
title: "haz_do callout: note"
date: 2026-10-08T09:00:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type note."
  desc_long: "Note is the default callout. This page shows a titled note, a note with no title, and Markdown in the body."
---

Type **note**. This is also the default when `type` is omitted. Large sticky-note icon, title and body in the second column.

{{< haz_do add="callout" type="note" title="Note" >}}
Neutral supporting information. No action required.
{{< /haz_do >}}

## Test samples

No title. Icon and body only.

{{< haz_do add="callout" type="note" >}}
This note has no title.
{{< /haz_do >}}

Markdown in the body: bold and a list.

{{< haz_do add="callout" type="note" title="With Markdown" >}}
A **bold** word belongs in the body.

- first point
- second point
{{< /haz_do >}}
