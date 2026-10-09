---
title: "haz_do list: ordered"
date: 2026-10-09T09:10:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do list with numbers."
  desc_long: "An ordered list inside haz_do list. Markdown 1. supplies the numbers. A plain ol on the same page stays plain."
---

Type **list**. Numbers come from a Markdown ordered list.

{{< haz_do add="list" title="Publish a post" >}}
1. Write the Markdown.
2. Put a blank line between shortcodes.
3. Rebuild the site.
{{< /haz_do >}}

No title.

{{< haz_do add="list" >}}
1. Open the file.
2. Save it.
{{< /haz_do >}}

A plain ordered list, outside `haz_do`, stays plain.

1. First.
2. Second.
