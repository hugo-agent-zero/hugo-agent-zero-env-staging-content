---
title: "haz_do callout: sad"
date: 2026-10-08T12:30:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type sad."
  desc_long: "Sad callout with a frown icon. Same yellow as tip, caution, and happy. Samples cover a title, no title, and Markdown in the body."
---

Type **sad**. Frown icon. Same yellow as tip, caution, and happy. Nothing is on fire.

{{< haz_do add="callout" type="sad" title="Sad" >}}
This did not work out.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="sad" >}}
This sad callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="sad" title="With Markdown" >}}
The preview **failed** to build.

- missing image
- bad front matter
{{< /haz_do >}}
