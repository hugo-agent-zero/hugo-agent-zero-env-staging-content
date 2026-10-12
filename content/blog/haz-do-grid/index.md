---
title: "haz_do grid"
date: 2026-10-12T08:00:00-04:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Dogfood haz_do grid."
  desc_long: "Grid is a wrapper. Each element inside is a cell. The count picks the columns."
---

Type **grid**. Paste one element per cell. A heading and a paragraph stay one cell because they sit inside that element. Two cells stay a pair until the phone. Four cells are one row on a wide screen, two by two on a tablet, and a stack on a phone.

## Two

{{< haz_do add="grid" >}}
<a class="haz_do_grid__item" href="/blog/">
  <h3>Write</h3>
  <p>Draft the page in Markdown.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Ship</h3>
  <p>Merge, then fast-forward the tag.</p>
</a>
{{< /haz_do >}}

## Four

{{< haz_do add="grid" >}}
<a class="haz_do_grid__item" href="/blog/">
  <h3>Write</h3>
  <p>Draft the page in Markdown.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Ship</h3>
  <p>Merge, then fast-forward the tag.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Notes</h3>
  <p>Leave a trail for the next pass.</p>
</a>
<a class="haz_do_grid__item" href="/blog/">
  <h3>Markup</h3>
  <p>One element is one cell.</p>
</a>
{{< /haz_do >}}

Paste pattern:

```
{{</* haz_do add="grid" */>}}
<a class="haz_do_grid__item" href="/docs/">
  <h3>Quickstart</h3>
  <p>Get running in five minutes.</p>
</a>
{{</* /haz_do */>}}
```
