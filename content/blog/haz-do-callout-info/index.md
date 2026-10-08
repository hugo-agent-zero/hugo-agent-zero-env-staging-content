---
title: "haz_do callout: info"
date: 2026-10-08T09:20:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type info."
  desc_long: "Info callout with a circle-info icon. Samples cover a title, no title, and Markdown in the body."
---

Type **info**. Circle-info icon. Related context, not a warning.

{{< haz_do add="callout" type="info" title="Info" >}}
This build needs Hugo 0.146 or newer.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="info" >}}
This info callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="info" title="With Markdown" >}}
See the [Hugo docs](https://gohugo.io/documentation/) for shortcode inner content.

A second paragraph should sit under the first, inside the same column as the title.
{{< /haz_do >}}
