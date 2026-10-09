---
title: "haz_do list"
date: 2026-10-09T09:00:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do list."
  desc_long: "List is a wrapper around a Markdown ul or ol. A plain list on the same page stays plain."
---

Type **list**. Optional title. The body is a normal Markdown list. Write `1.` for numbers or `-` for bullets. The shortcode only adds the block chrome.

{{< haz_do add="list" title="Publish a post" >}}
1. Write the Markdown.
2. Put a blank line between shortcodes.
3. Rebuild the site.
{{< /haz_do >}}

## Test samples

No title.

{{< haz_do add="list" >}}
1. Open the file.
2. Save it.
{{< /haz_do >}}

Bullets.

{{< haz_do add="list" title="Bring" >}}
- A pen.
- The draft.
- Time to read it once.
{{< /haz_do >}}

A plain ordered list, outside `haz_do`, stays plain.

1. First.
2. Second.

A plain bullet list stays plain too.

- One.
- Two.

Paste pattern:

```
{{</* haz_do add="list" title="Title" */>}}
1. First step.
2. Second step.
{{</* /haz_do */>}}

{{</* haz_do add="list" title="Title" */>}}
- First item.
- Second item.
{{</* /haz_do */>}}
```
