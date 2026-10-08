---
title: "haz_do callout: tip"
date: 2026-10-08T09:10:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type tip."
  desc_long: "Tip callout with a lightbulb icon. Samples cover a title, no title, and Markdown in the body."
---

Type **tip**. Lightbulb icon. Use it for a short suggestion.

{{< haz_do add="callout" type="tip" title="Pro tip" >}}
Keep callouts short. One or two sentences read best.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="tip" >}}
This tip has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="tip" title="With Markdown" >}}
Prefer `add="callout"` over a new shortcode.

1. Pick a type.
2. Add a title if you need one.
{{< /haz_do >}}
