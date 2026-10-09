---
title: "haz_do list: bullets"
date: 2026-10-09T09:20:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do list with bullets."
  desc_long: "A bullet list inside haz_do list. Markdown - supplies the bullets. A plain ul on the same page stays plain."
---

Type **list**. Bullets come from a Markdown list.

{{< haz_do add="list" title="Bring" >}}
- A pen.
- The draft.
- Time to read it once.
{{< /haz_do >}}

No title.

{{< haz_do add="list" >}}
- Open the file.
- Save it.
{{< /haz_do >}}

A plain bullet list, outside `haz_do`, stays plain.

- One.
- Two.
