---
title: "haz_do grid, three"
date: 2026-10-12T08:10:00-04:00
authors:
  - author_0001
categories:
  - Notes
tags:
  - hugo
  - demo
  - haz-do
params:
  desc_short: "Three cells in a haz_do grid."
  desc_long: "Three is one row on a wide screen. On a tablet the third cell hangs at the same width."
---

Three cells. Wide screen is one row of three. Tablet is two, then one left over. The leftover stays the width of the others.

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
{{< /haz_do >}}
