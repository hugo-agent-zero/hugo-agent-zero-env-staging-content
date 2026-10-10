---
title: "haz_do tabs"
date: 2026-10-09T10:00:00-07:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do tabs."
  desc_long: "Tabs is a CSS-only set of panels. Each nested tab is a radio and a label. No script."
---

Type **tabs**. Each tab is a radio and a label. The browser switches the panel. No script. A panel is Markdown unless `html=true`, which passes the markup through.

{{< haz_do add="tabs" embla=true >}}

{{< haz_do add="tab" title="Write Test" >}}
Use a blank line between tabs.

A code fence is just a panel:

~~~
hugo server
~~~
{{< /haz_do >}}

{{< haz_do add="tab" title="Ship Test" >}}
1. Merge core.
2. Fast-forward `v1.x.x`.
{{< /haz_do >}}

{{< haz_do add="tab" title="Notes Test" >}}
- CSS only.
- The browser switches the panel.
{{< /haz_do >}}

{{< haz_do add="tab" title="Markup Test" html=true >}}
<p>This <strong>panel</strong> is HTML, same pass-through as <code>haz_img</code>.</p>
{{< /haz_do >}}

{{< /haz_do >}}

## Another set

{{< haz_do add="tabs" >}}

{{< haz_do add="tab" title="Alpha" >}}
First panel of a second set.
{{< /haz_do >}}

{{< haz_do add="tab" title="Beta" >}}
Second panel. It does not change the set above.
{{< /haz_do >}}

{{< /haz_do >}}

Paste pattern:

```
{{</* haz_do add="tabs" */>}}

{{</* haz_do add="tab" title="One" */>}}
First panel.
{{</* /haz_do */>}}

{{</* haz_do add="tab" title="Two" */>}}
Second panel.
{{</* /haz_do */>}}

{{</* haz_do add="tab" title="Markup" html=true */>}}
<p>Raw <strong>HTML</strong>.</p>
{{</* /haz_do */>}}

{{</* /haz_do */>}}
```
