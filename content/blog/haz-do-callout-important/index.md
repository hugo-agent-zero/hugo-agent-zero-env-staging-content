---
title: "haz_do callout: important"
date: 2026-10-08T12:00:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do callout type important."
  desc_long: "Important callout with a star icon. Same blue as info and peace. Samples cover a title, no title, and Markdown in the body."
---

Type **important**. Star icon. Same blue as info and peace. Read this. It is not a hazard.

{{< haz_do add="callout" type="important" title="Important" >}}
Read this before you continue. Nothing is on fire.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="callout" type="important" >}}
This important callout has no title.
{{< /haz_do >}}

Markdown in the body.

{{< haz_do add="callout" type="important" title="With Markdown" >}}
A **bold** word belongs in the body.

- first point
- second point
{{< /haz_do >}}
