---
title: "haz_do callout: warning"
date: 2026-10-08T09:30:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type warning."
  desc_long: "Warning callout with a triangle icon. Samples cover a title, no title, and Markdown in the body."
---

Type **warning**. Triangle icon. Something can go wrong.

{{< haz_do add="callout" type="warning" title="Warning" >}}
This overwrites the existing file.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="warning" >}}
This warning has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="warning" title="With Markdown" >}}
Check **both** of these before you continue:

- the target path
- that you meant to replace it
{{< /haz_do >}}
