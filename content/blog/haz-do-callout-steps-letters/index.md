---
title: "haz_do callout: steps letters"
date: 2026-10-16T12:09:00-04:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type steps with letters."
  desc_long: "Same steps type. step= can be A, B, C or a short word, not only 1, 2, 3."
---

Same **steps** type. `step` is a string.

{{< haz_do add="callout" type="steps" step="A" title="Measure" >}}
Pick the column width first. Headlines follow.
{{< /haz_do >}}

{{< haz_do add="callout" type="steps" step="B" title="Face" >}}
`--haz_font_headline` is the swap. Not a restyle.
{{< /haz_do >}}

{{< haz_do add="callout" type="steps" step="Go" title="Ship" >}}
A short word still fits the circle.
{{< /haz_do >}}
